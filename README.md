# Intorduction
![](https://img.shields.io/github/last-commit/JBoRu/Awesome-KBQA?color=blue)

Knowledge Based Question Answering (KBQA) aims to answer factual questions based on the provided knowledge base (KB). This repo contains all of the KBQA relevant resources as soon as possible, including the latest paper list, open source toolkits (or repo), and the leaderboard of benchmarks.

This list summarizes the relevant KBQA papers in recent years, and divides them into three categories: semantic parsing-based approaches (SP), information retrieval-based approaches (IR), and other approaches (Other). 

It is organized according to our lateset survey paper: [Complex Knowledge Base Question Answering: A Survey](https://arxiv.org/pdf/2108.06688.pdf). Welcome to follow.

## Contents
- [Datasets](#datasets)
- [Leaderboard](#leaderboard)
- [Paper List](#paper_list)
  - [Survey](#survey)
  - [Simple KBQA](#simple)
    - [Semantic Parsing-based Methods](#simple_sp)
    - [Information retrieval-based Methods](#simple_ir)
    - [Other Methods](#simple_oth)
  - [Complex KBQA](#complex)
    - [Semantic Parsing-based Methods](#complex_sp)
    - [Information retrieval-based Methods](#complex_ir)
    - [Other Methods](#complex_oth)
- [Open Source](#open_source)

<a name="datasets"></a>
## Datasets And Leaderboard
1. **WebQuestions**: "Semantic parsing on freebase from question-answer pairs". `EMNLP(2013)`. [[PDF](https://www.aclweb.org/anthology/D13-1160.pdf)] [[Homepage](https://worksheets.codalab.org/worksheets/0xba659fe363cb46e7a505c5b6a774dc8a)][[Leaderboard]]
2. **ComplexQuestions**: "Constraint based question answering with knowledge graph". `COLING(2016)`. [[PDF](https://www.aclweb.org/anthology/C16-1236.pdf)] [[Homepage](https://github.com/JunweiBao/MulCQA/tree/ComplexQuestions)][[Leaderboard]]
3. **WebQuestionsSP**: "The value of semantic parse labeling for knowledge base question answering". `ACL(2016)`. [[PDF](https://www.aclweb.org/anthology/P16-2033.pdf)] [[Homepage](https://www.microsoft.com/en-us/download/details.aspx?id=52763)][[Leaderboard]]
4. **ComplexWebQuestions**: "The web as a knowledge-base for answering complex questions". `NAACL(2018)`. [[PDF](https://allenai.org/data/complexwebquestions)] [[Homepage](https://allenai.org/data/complexwebquestions)][[Leaderboard]]
5. **QALD**: "Evaluating question answering over linked data". `Web  Semantics Science Services And Agents On The World Wide Web(2013)`. [[PDF](https://www.researchgate.net/publication/241166948_Evaluating_Question_Answering_over_Linked_Data)] [[Homepage](http://qald.aksw.org/)][[Leaderboard]]
6. **LC-QuAD 1.0**: "Lc-quad: A corpus for complex question answering over knowledge graphs". `ISWC(2017)`. [[PDF](https://jens-lehmann.org/files/2017/iswc_lcquad.pdf)] [[Homepage](http://lc-quad.sda.tech/lcquad1.0.html)][[Leaderboard]]
7. **LC-QuAD 2.0**: "“Lc-quad 2.0: A large dataset for complex question answering over wikidata and dbpedia". `ISWC(2019)`. [[PDF](https://jens-lehmann.org/files/2019/iswc_lcquad2.pdf)] [[Homepage](http://lc-quad.sda.tech/)][[Leaderboard]]
8. **MetaQA Vanilla**: "Variational reasoning for question answering with knowledge graph". `AAAI(2018)`. [[PDF](https://arxiv.org/pdf/1709.04071.pdf)] [[Homepage](https://github.com/yuyuz/MetaQA)][[Leaderboard]]
9. **CFQ**: "Measuring compositional generalization: A comprehensive method on realistic data". `ICLR(2020)`. [[PDF](https://arxiv.org/pdf/1912.09713.pdf)] [[Homepage](https://github.com/google-research/google-research/tree/master/cfq)][[Leaderboard]]
10. **KQA Pro**: "Kqa pro: A large diagnostic dataset for complex question answering over knowledge base". `arXiv(2020)`. [[PDF](https://arxiv.org/pdf/2007.03875.pdf)]  [[Homepage](http://thukeg.gitee.io/kqa-pro/)][[Leaderboard]]
11. **GrailQA**: "Beyond I.I.D.: three levels of generalization for question answering on knowledge bases". `WWW(2021)`. [[PDF](https://arxiv.org/pdf/2011.07743.pdf)] [[Homepage](https://dki-lab.github.io/GrailQA/)][[Leaderboard]]

<a name="paper_list"></a>
## Paper List
<a name="survey"></a>
### Survey
1. **Core techniques of question answering systems over knowledge bases: a survey**. *Dennis Diefenbach, Vanessa Lopez, Kamal Singh, Pierre Maret*. `Knowledge and Information Systems(2017)`. [[PDF](https://link.springer.com/article/10.1007/s10115-017-1100-y)]
4. **A Survey of Question Answering over Knowledge Base**. *Peiyun Wu, Xiaowang Zhang, Zhiyong Feng*. `CCIS(2019)`. [[PDF](https://link.springer.com/chapter/10.1007/978-981-15-1956-7_8)]
1. **A Survey on Complex Question Answering over Knowledge Base: Recent Advances and Challenges**. *Bin Fu, Yunqi Qiu, Chengguang Tang, Yang Li, Haiyang Yu, Jian Sun*. `arXiv(2020)`. [[PDF](https://arxiv.org/pdf/2007.13069.pdf)]
5. **Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs**. *Nilesh Chakraborty, Denis Lukovnikov, Gaurav Maheshwari, Priyansh Trivedi, Jens Lehmann, Asja Fischer*. `WIDM(2021)`. [[PDF](https://onlinelibrary.wiley.com/doi/epdf/10.1002/widm.1389)]
6. **A Survey on Complex Knowledge Base Question Answering: Methods, Challenges and Solutions**. *Yunshi Lan, Gaole He, Jinhao Jiang, Jing Jiang, Wayne Xin Zhao, Ji-Rong Wen*. `IJCAI(2021)`. [[PDF](https://arxiv.org/pdf/2105.11644.pdf)]

<a name="simple"></a>
### Simple KBQA
<a name="simple_sp"></a>
#### Semantic Parsing-based Methods 
1. **Template-based question answering over RDF data**. *Unger, Christina, Lorenz Bühmann, Jens Lehmann, A. N. Ngomo, D. Gerber, P. Cimiano*. `WWW(2012)`. [[PDF](https://perso.liris.cnrs.fr/pierre-antoine.champin/enseignement/semweb/_static/articles/unger_2012.pdf)]
2. **Large-scale semantic parsing via schema matching and lexicon extension**. *Qingqing Cai, Alexander Yates*. `ACL(2013)`. [[PDF](https://www.aclweb.org/anthology/P13-1042.pdf)]
4. **Semantic parsing on freebase from question-answer pairs**. *Jonathan Berant, Andrew Chou, Roy Frostig, Percy Liang*. `EMNLP(2013)`. [[PDF](https://www.aclweb.org/anthology/D13-1160.pdf)]
5. **Large-scale semantic parsing without question-answer pairs**. *Siva Reddy, Mirella Lapata, Mark Steedman*. `TACL(2014)`. [[PDF](https://www.aclweb.org/anthology/Q14-1030.pdf)]
6. **Semantic parsing for single relation question answering**. *Wen-tau Yih, Xiaodong He, Christopher Meek*. `ACL(2014)`. [[PDF](https://www.aclweb.org/anthology/P14-2105.pdf)]
7. **Information extraction over structured data: Question answering with Freebase**. *Xuchen Yao, Benjamin Van Durme*. `ACL(2014)`. [[PDF](https://www.aclweb.org/anthology/P14-1090.pdf)]
8. **Semantic parsing via staged query graph generation: Question answering with knowledge base**. *Wen-tau Yih, Ming-Wei Chang, Xiaodong He, Jianfeng Gao*. `ACL(2015)`. [[PDF](https://www.aclweb.org/anthology/P15-1128.pdf)]
9. **Simple question answering by attentive convolutional neural network**. *Wenpeng Yin, Mo Yu, Bing Xiang, Bowen Zhou, Hinrich Schütze*. `COLING(2016)`. [[PDF](https://www.aclweb.org/anthology/C16-1164.pdf)]
11. **Learning to compose neural networks for question answering**. *Jacob Andreas, Marcus Rohrbach, Trevor Darrell, Dan Klein*. `NAACL(2016)`. [[PDF](https://arxiv.org/pdf/1601.01705.pdf)] [[Code](https://github.com/jacobandreas/nmn2)]
10. **Knowledge base question answering with a matching-aggregation model and question-specific contextual relations**. *Yunshi Lan, Shuohang Wang, Jing Jiang*. `TASLP(2019)`. [[PDF](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5904&context=sis_research)]
<a name="simple_ir"></a>
#### Information retrieval-based Methods
1. **Open question answering with weakly supervised embedding models**. *Antoine Bordes, Jason Weston, Nicolas Usunier*. `Machine Learning and Knowledge Discovery in Databases(2014)`. [[PDF](https://arxiv.org/pdf/1404.4326.pdf)]
3. **Question answering with subgraph embeddings**. *Antoine Bordes, Sumit Chopra, Jason Weston*. `EMNLP(2014)`. [[PDF](https://arxiv.org/pdf/1406.3676.pdf)]
1. **Larges cale simple question answering with memory networks**. *Antoine Bordes, Nicolas Usunier, Sumit Chopra, Jason Weston*. `arXiv(2015)`. [[PDF](https://arxiv.org/pdf/1506.02075.pdf)] [[Code](https://github.com/Jerryzhao-z/simple-question-answering-with-memory-networks)]
5. **Question answering over freebase with multi-column convolutional neural networks**. *Li Dong, Furu Wei, Ming Zhou, Ke Xu*. `ACL(2015)`. [[PDF](https://www.aclweb.org/anthology/P15-1026.pdf)]
4. **Question answering over knowledge base using factual memory networks**. *Sarthak Jain*. `NAACL(2016)`. [[PDF](https://www.aclweb.org/anthology/N16-2016.pdf)]
6. **An end-to-end model for question answering over knowledge base with cross-attention combining global knowledge**. *Yanchao Hao, Yuanzhe Zhang, Kang Liu, Shizhu He, Zhanyi Liu, Hua Wu, Jun Zhao*. `ACL(2017)`. [[PDF](https://www.aclweb.org/anthology/P17-1021.pdf)]
6. **Bidirectional Attentive Memory Networks for Question Answering over Knowledge Bases**. *Yu Chen, Lingfei Wu, Mohammed J. Zaki*. `NAACL(2019)`. [[PDF](https://arxiv.org/pdf/1903.02188.pdf)] [[Code](https://github.com/hugochan/BAMnet?utm_source=catalyzex.com)]
<a name="simple_oth"></a>
#### Other Methods
1. **Hybrid question answering over knowledge base and free text**. *Kun Xu, Yansong Feng, Songfang Huang, Dongyan Zhao*. `COLING(2016)`. [[PDF](https://www.aclweb.org/anthology/C16-1226.pdf)]
4. **Question answering on freebase via relation extraction and textual evidence**. *Kun Xu, Siva Reddy, Yansong Feng, Songfang Huang, Dongyan Zhao*. `ACL(2016)`. [[PDF](https://www.aclweb.org/anthology/P16-1220.pdf)] [[Code](https://github.com/syxu828/QuestionAnsweringOverFB)]
1. **Improved neural relation detection for knowledge base question answering**. *Mo Yu, Wenpeng Yin, Kazi Saidul Hasan, Cicero dos Santos, Bing Xiang, Bowen Zhou*. `ACL(2017)`. [[PDF](https://www.aclweb.org/anthology/P17-1053.pdf)]
5. **KBQA: learning question answering over QA corpora and knowledge bases**. *Wanyun Cui, Yanghua Xiao, Haixun Wang, Yangqiu Song, Seung-won Hwang, Wei Wang*. `VLDB(2017)`. [[PDF](https://arxiv.org/pdf/1903.02419.pdf)]
2. **Knowledge base question answering with topic units**. *Yunshi Lan , Shuohang Wang, Jing Jiang*. `IJCAI(2019)`. [[PDF](https://www.ijcai.org/proceedings/2019/0701.pdf)]
3. **Retrieval, Re-ranking and Multi-task Learning for Knowledge-Base Question Answering**. *Zhiguo Wang, Patrick Ng, Ramesh Nallapati, Bing Xiang*. `EACL(2021)`. [[PDF](https://www.aclweb.org/anthology/2021.eacl-main.26.pdf)].

<a name="complex"></a>
### Complex KBQA
<a name="complex_sp"></a>
#### Semantic Parsing-based Methods
1. **Automated template generation for question answering over knowledge graphs**. *Abujabal, Abdalghani, Mohamed Yahya, Mirek Riedewald, G. Weikum*. `WWW(2017)`. [[PDF](http://papers.www2017.com.au.s3-website-ap-southeast-2.amazonaws.com/proceedings/p1191.pdf)]
1. **Neural symbolic machines: Learning semantic parsers on Freebase with weak supervision**. *Chen Liang, Jonathan Berant, Quoc Le, Kenneth D. Forbus, Ni Lao*. `ACL(2017)`. [[PDF](https://arxiv.org/pdf/1611.00020.pdf)] [[Code](https://github.com/agarwl/neural-symbolic-machines?utm_source=catalyzex.com)]
1. **Knowledge base question answering via encoding of complex query graphs**. *Kangqi Luo, Fengli Lin, Xusheng Luo, Kenny Zhu*. `EMNLP(2018)`. [[PDF](https://www.aclweb.org/anthology/D18-1242.pdf)] [[Code](https://github.com/lkq1992yeah/CompQA)]
1. **Neverending learning for open-domain question answering over knowledge bases**. *Abujabal, Abdalghani, Rishiraj Saha Roy, Mohamed Yahya, G. Weikum*. `WWW(2018)`. [[PDF](https://myahya.org/publications/neqa-abujabal-www2018.pdf)]
1. **A state-transition framework to answer complex questions over knowledge base**. *Sen Hu, Lei Zou, Xinbo Zhang*. `EMNLP(2018)`. [[PDF](https://www.aclweb.org/anthology/D18-1234.pdf)]
1. **Question answering over knowledge graphs: Question understanding via template decomposition**. *Weiguo Zheng, Jeffrey Xu Yu, Lei Zou, Hong Cheng*. `VLDB(2018)`. [[PDF](http://www.vldb.org/pvldb/vol11/p1373-zheng.pdf)]
1. **Learning to answer complex questions over knowledge bases with query composition**. *Bhutani, Nikita, Xinyi Zheng, H. Jagadish*. `CIKM(2019)`. [[PDF](https://dl.acm.org/doi/10.1145/3357384.3358033)]
1. **UHop: An unrestricted-hop relation extraction framework for knowledge-based question answering**. *Zi-Yuan Chen, Chih-Hung Chang, Yi-Pei Chen, Jijnasa Nayak, Lun-Wei Ku*. `NAACL(2019)`. [[PDF](https://arxiv.org/pdf/1904.01246.pdf)]
1. **Multi-hop knowledge base question answering with an iterative sequence matching model**. *	Yunshi Lan, Shuohang Wang, Jing Jiang*. `ICDM(2019)`. [[PDF](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5939&context=sis_research)]
1. **Learning to rank query graphs for complex question answering over knowledge graphs**. *Gaurav Maheshwari, Priyansh Trivedi, Denis Lukovnikov, Nilesh Chakraborty, Asja Fischer, Jens Lehmann*. `ISWC(2019)`. [[PDF](https://arxiv.org/pdf/1811.01118.pdf)] [[Code](https://github.com/AskNowQA/KrantikariQA)]
1. **Complex program induction for querying knowledge bases in the absence of gold programs**. *Amrita Saha, Ghulam Ahmed Ansari, Abhishek Laddha, Karthik Sankaranarayanan, Soumen Chakrabarti*. `TACL(2019)`. [[PDF](https://www.aclweb.org/anthology/Q19-1012.pdf)][[Code](https://github.com/CIPITR/CIPITR)]
1. **Leveraging Frequent Query Substructures to Generate Formal Queries for Complex Question Answering**. *Jiwei Ding, Wei Hu, Qixin Xu, Yuzhong Qu*. `EMNLP(2019)`. [[PDF](https://arxiv.org/pdf/1908.11053.pdf)]
1. **Hierarchical query graph generation for complex question answering over knowledge graph**. *Qiu, Yunqi, K. Zhang, Yuanzhuo Wang, Xiaolong Jin, Long Bai, Saiping Guan, Xueqi Cheng*. `CIKM(2020)`. [[PDF](https://dl.acm.org/doi/abs/10.1145/3340531.3411888)]
1. **SPARQA: skeleton-based semantic parsing for complex questions over knowledge bases**. *Yawei Sun, Lingling Zhang, Gong Cheng, Yuzhong Qu*. `AAAI(2020)`. [[PDF](https://arxiv.org/pdf/2003.13956.pdf)] [[Code](https://github.com/nju-websoft/SPARQA)]
1. **Formal query building with query structure prediction for complex question answering over knowledge base**. *Yongrui Chen, Huiying Li, Yuncheng Hua, Guilin Qi*. `IJCAI(2020)`. [[PDF](https://www.ijcai.org/proceedings/2020/0519.pdf)] [[Code](https://github.com/Bahuia/AQGNet)]
1. **Query graph generation for answering multi-hop complex questions from knowledge bases**. *Yunshi Lan, Jing Jiang*. `ACL(2020)`. [[PDF](https://www.aclweb.org/anthology/2020.acl-main.91.pdf)] [[Code](https://github.com/lanyunshi/Multi-hopComplexKBQA)]
1. **Answering Complex Questions by Combining Information from Curated and Extracted Knowledge Bases**. *Nikita Bhutani, Xinyi Zheng, Kun Qian, Yunyao Li, H. Jagadish*. `ACL(2020)`. [[PDF](https://www.aclweb.org/anthology/2020.nli-1.1.pdf)]
1. **Leveraging abstract meaning representation for knowledge base question answering**. *Pavan Kapanipathi, Ibrahim Abdelaziz, Srinivas Ravishankar, Salim Roukos, Alexander Gray, Ramon Astudillo, Maria Chang, Cristina Cornelio, Saswati Dana, Achille Fokoue, Dinesh Garg, Alfio Gliozzo, Sairam Gurajada, Hima Karanam, Naweed Khan, Dinesh Khandelwal, Young-Suk Lee, Yunyao Li, Francois Luus, Ndivhuwo Makondo, Nandana Mihindukulasooriya, Tahira Naseem, Sumit Neelam, Lucian Popa, Revanth Reddy, Ryan Riegel, Gaetano Rossiello, Udit Sharma, G P Shrivatsa Bhargav, Mo Yu*. `Findings of ACL(2021)`. [[PDF](https://arxiv.org/pdf/2012.01707.pdf)]
<a name="complex_ir"></a>
#### Information retrieval-based Methods
1. **Open domain question answering based on text enhanced knowledge graph with hyperedge infusion**. *Jiale Han, Bo Cheng, Xu Wang*. `Findings of EMNLP(2018)`. [[PDF](https://www.aclweb.org/anthology/2020.findings-emnlp.133.pdf)]
1. **Open domain question answering using early fusion of knowledge bases and text**. *Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen*. `EMNLP(2018)`. [[PDF](https://www.aclweb.org/anthology/D18-1455.pdf)] [[Code](https://github.com/OceanskySun/GraftNet?utm_source=catalyzex.com)]
1. **An interpretable reasoning network for multi-relation question answering**. *Mantong Zhou, Minlie Huang, Xiaoyan Zhu*. `COLING(2018)`. [[PDF](https://www.aclweb.org/anthology/C18-1171.pdf)] [[Code](https://github.com/zmtkeke/IRN?utm_source=catalyzex.com)]
1. **Variational reasoning for question answering with knowledge graph**. *Yuyu Zhang, Hanjun Dai, Zornitsa Kozareva, Alexander J. Smola, Le Song*. `AAAI(2018)`. [[PDF](https://arxiv.org/pdf/1709.04071.pdf)] [[Code](https://github.com/yuyuz/Variational-Reasoning-Networks?utm_source=catalyzex.com)]
1. **Enhancing key-value memory neural networks for knowledge based question answering**. *Kun Xu, Yuxuan Lai, Yansong Feng, Zhiguo Wang*. `NAACL(2019)`. [[PDF](https://www.aclweb.org/anthology/N19-1301.pdf)]
1. **Pullnet: Open domain question answering with iterative retrieval on knowledge bases and text**. *Haitian Sun, Tania Bedrax-Weiss, William W. Cohen*. `EMNLP(2019)`. [[PDF](https://arxiv.org/pdf/1904.09537.pdf)]
1. **Improving question answering over incomplete kbs with knowledge-aware reader**. *Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang*. `ACL(2019)`. [[PDF](https://www.aclweb.org/anthology/P19-1417.pdf)] [[Code](https://github.com/xwhan/Knowledge-Aware-Reader)]
1. **Answering Complex Questions by Joining Multi-Document Evidence with Quasi Knowledge Graphs**. *Xiaolu Lu, Soumajit Pramanik, Rishiraj Saha Roy, Abdalghani Abujabal, Yafang Wang, Gerhard Weikum*. `SIGIR(2019)`. [[PDF](https://arxiv.org/pdf/1908.00469.pdf)]
1. **Two-phase Hypergraph Based Reasoning With Dynamic Relations For Multi-Hop KBQA**. *Jiale Han, Bo Cheng, Xu Wang*. `IJCAI(2020)`. [[PDF](https://www.ijcai.org/Proceedings/2020/0500.pdf)]
1. **Improving multi-hop question answering over knowledge graphs using knowledge base embeddings**. *Apoorv Saxena, Aditay Tripathi, Partha Talukdar*. `ACL(2020)`. [[PDF](https://www.aclweb.org/anthology/2020.acl-main.412.pdf)] [[Code](https://github.com/malllabiisc/EmbedKGQA)]
1. **Stepwise reasoning for multi-relation question answering over knowledge graph with weak supervision**. *Qiu, Yunqi, Yuanzhuo Wang, Xiaolong Jin, K. Zhang*. `WSDM(2020)`. [[PDF](https://dl.acm.org/doi/abs/10.1145/3336191.3371812)] [[Code](https://github.com/DanSeb1295/multi-relation-QA-over-KG)]
1. **Modeling Long-distance Node Relations for KBQA with Global Dynamic Graph**. *Xu Wang, Shuai Zhao, Jiale Han, Bo Cheng, Hao Yang, Jianchang Ao, Zhenzi Li*. `COLING(2020)`. [[PDF](https://www.aclweb.org/anthology/2020.coling-main.231.pdf)]
1. **Improving multi-hop knowledge base question answering by learning intermediate supervision signals**. *Gaole He, Yunshi Lan, Jing Jiang, Wayne Xin Zhao, Ji-Rong Wen*. `WSDM(2021)`. [[PDF](https://arxiv.org/pdf/2101.03737.pdf)] [[Code](https://github.com/RichardHGL/WSDM2021_NSM)]
<a name="complex_oth"></a>
#### Other Methods
1. **QUINT: Interpretable Question Answering over Knowledge Bases**. *Abdalghani Abujabal, Rishiraj Saha Roy, Mohamed Yahya, Gerhard Weikum*. `EMNLP(2017)`. [[PDF](https://www.aclweb.org/anthology/D17-2011.pdf)]
1. **Modeling Semantics with Gated Graph Neural Networks for Knowledge Base Question Answering**. *Daniil Sorokin, Iryna Gurevych*. `COLING(2018)`. [[PDF](https://www.aclweb.org/anthology/C18-1280.pdf)] [[Code](https://github.com/UKPLab/coling2018-graph-neural-networks-question-answering?utm_source=catalyzex.com)]
1. **PERQ: Predicting, Explaining, and Rectifying Failed Questions in KB-QA Systems**. *Zhiyong Wu, Ben Kao, Tien-Hsuan Wu, Pengcheng Yin, Qun Liu*. `WSDM(2020)`. [[PDF](https://dl.acm.org/doi/abs/10.1145/3336191.3371782)]
1. **Few-Shot Complex Knowledge Base Question Answering via Meta Reinforcement Learning**. *Yuncheng Hua, Yuan-Fang Li, Gholamreza Haffari, Guilin Qi, Tongtong Wu*. `EMNLP(2020)`. [[PDF](https://dl.acm.org/doi/abs/10.1145/3336191.3371782)] [[Code](https://github.com/DevinJake/MRL-CQA)]
1. **Question Answering Over Temporal Knowledge Graphs**. *Apoorv Saxena, Soumen Chakrabarti, Partha Talukdar*. `ACL(2021)`. [[PDF](https://dl.acm.org/doi/abs/10.1145/3336191.3371782)] [[Code](https://github.com/apoorvumang/CronKGQA)]
1. **Improving Zero-Shot Cross-lingual Transfer for Multilingual Question Answering over Knowledge Graph**. *Yucheng Zhou, Xiubo Geng, Tao Shen, Wenqiang Zhang, Daxin Jiang*. `NAACL(2021)`. [[PDF](https://www.aclweb.org/anthology/2021.naacl-main.465.pdf)]
1. **Complex Question Answering on knowledge graphs using machine translation and multi-task learning**. *Saurabh Srivastava, Mayur Patidar, Sudip Chowdhury, Puneet Agarwal, Indrajit Bhattacharya, Gautam Shroff*. `EACL(2021)`. [[PDF](https://www.aclweb.org/anthology/2021.eacl-main.300.pdf)]

<a name="open_source"></a>
## Open Source

## Citation
If you found this list useful, please consider citing this paper:
```
@inproceedings{Lan-KBQASurvey-2021,
  author    = {Yunshi Lan and
               Gaole He and
               Jinhao Jiang and
               Jing Jiang and
               Wayne Xin Zhao and
               Ji{-}Rong Wen},
  title     = {Complex Knowledge Base Question Answering: A Survey},
  booktitle = {{arXiv}},
  year      = {2021},
}
```
