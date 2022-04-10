# WebQuestionsSP

**WebQuestionsSP**<sup>[[1]](#myfootnote1)</sup> is the annotated version of WebQuestions, which contains questions that require a 1 or 2-hop relation path to arrive at the answer entity. 
More specifically, about 40% of the questions require a 2-hop relation to reach the answer. Freebase is its backgound KB. Originally, it splits into 3,298 questions 
as train set and 1,639 questions as test set. 

This dataset can be downloaded via the [link](https://www.microsoft.com/en-us/download/details.aspx?id=52763).


## Leaderboard 
| Year | Type  | F1 | Acc | Reported by | Official Repo |
|:----:|:----:|:--:|:---:|:-----------:| :-----------: |
| 2022 | IR-based | - | 83.2 | [Zhang. et al](https://arxiv.org/pdf/2202.13296.pdf) | [Repo](https://github.com/RUCKBReasoning/SubgraphRetrievalKBQA) |
| 2021 | IR-based | - | 68.6 | [Feng. et al](https://aclanthology.org/2021.findings-emnlp.159.pdf) | [Repo](https://github.com/RUCKBReasoning/NumKBQA) |
| 2021 | IR-based | - | 74.3 | [He. et al](https://arxiv.org/pdf/2101.03737.pdf) | [Repo](https://github.com/RichardHGL/WSDM2021_NSM) |
| 2020 | SP-based | 72.0 | - | [Hua. et al](https://arxiv.org/pdf/2010.15881.pdf) | [Repo](https://github.com/DevinJake/NS-CQA) |
| 2020 | SP-based | 63.7 | - | [Zhu. et al](https://www.sciencedirect.com/science/article/pii/S0925231219312639) | - |
| 2020 | SP-based | 74.0 | - | [Lan. et al](https://aclanthology.org/2020.acl-main.91.pdf) | [Repo](https://github.com/lanyunshi/Multi-hopComplexKBQA) |
| 2020 | IR-based | - | 68.4 | [Han. et al](https://aclanthology.org/2020.findings-emnlp.133.pdf) | [Repo](https://github.com/malllabiisc/EmbedKGQA) |
| 2020 | IR-based | - | 66.6 | [Saxena. et al](https://aclanthology.org/2020.acl-main.412.pdf) | [Repo](https://github.com/malllabiisc/EmbedKGQA) |
| 2019 | IR-based | - | 68.1 | [Sun. et al](https://arxiv.org/pdf/1904.09537.pdf) | - |
| 2019 | IR-based | - | 67.2 | [Xiong. et al](https://aclanthology.org/P19-1417.pdf) | [Repo](https://github.com/xwhan/Knowledge-Aware-Reader) |
| 2019 | SP-based | 82.9 | - | [Saha. et al](https://aclanthology.org/Q19-1012.pdf) | - |
| 2019 | SP-based | 60.3 | - | [Bhutani. et al](https://dl.acm.org/doi/abs/10.1145/3357384.3358033) | - |
| 2019 | SP-based | - | 82.6 | [Chen. et al](https://arxiv.org/pdf/1904.01246.pdf) | - |
| 2018 | IR-based | - | 66.4 | [Sun. et al](https://arxiv.org/pdf/1809.00782.pdf) | [Repo](https://github.com/OceanskySun/GraftNet) |
| 2017 | SP-based | 69.0 | - | [Liang. et al](https://arxiv.org/pdf/1611.00020.pdf) | [Repo](https://github.com/theSparta/neural-symbolic-machines) |
| 2016 | SP-based | 66.8 | - | [Yih. et al](https://aclanthology.org/P16-2033.pdf) | - |
| 2016 | IR-based | - | 46.7 | [H. Miller. et al](https://arxiv.org/pdf/1606.03126.pdf) | - |

<!-- | 2022 | IR-based | - | 83.2 | [Zhang. et al](https://arxiv.org/pdf/2202.13296.pdf) | [Repo](https://github.com/RUCKBReasoning/SubgraphRetrievalKBQA) | -->


## References 
<a name="myfootnote1">[1]</a> Yih, Wen-tau, Matthew Richardson, Christopher Meek, Ming-Wei Chang, and Jina Suh. [The value of semantic parse labeling for knowledge base question answering.](http://anthology.aclweb.org/P16-2033) In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers), pp. 201-206. 2016.


[Go back to the README](../README.md)
