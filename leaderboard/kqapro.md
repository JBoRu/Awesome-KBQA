# KQA Pro

**KQA Pro**<sup>[[1]](#myfootnote1)</sup> is a large-scale dataset for Complex KBQA, where a compositional and highly-interpretable formal format, named Program, is defined to represent the reasoning process of complex questions. 
Compositional strategies are proposed to generate questions, corresponding SPARQLs, and Programs with a small number of templates, and the generated questions are then paraphrased to natural language questions (NLQ) 
by crowdsourcing, giving rise to around 120K diverse instances. SPARQL and Program depict two complementary solutions to answer complex questions, which can benefit a large spectrum of QA methods. Besides the QA task, 
This dataset can also serves for the semantic parsing task. In addition, it is currently the largest corpus of NLQ-to-SPARQL and NLQ-to-Program.

This dataset can be downloaded via the [link](http://thukeg.gitee.io/kqa-pro/).

## Leaderboard
| Model | Year | Type | Precision | Recall | F1 | Acc | Reported by | Official Repo |
|:-----:|:----:|:----:|:---------:|:------:|:--:|:---:|:-----------:| :-----------: |
| mBERT | 2021 | IR-based | 73.00 | - | 85.50 | - | [Zhou Y. et al](https://aclanthology.org/2021.naacl-main.465.pdf) | - |

## References
<a name="myfootnote1">[1]</a> Shi, Jiaxin, Shulin Cao, Liangming Pan, Yutong Xiang, Lei Hou, Juanzi Li, Hanwang Zhang, and Bin He. [KQA Pro: A Large-Scale Dataset with Interpretable Programs and Accurate SPARQLs for Complex Question Answering over Knowledge Base.](https://arxiv.org/pdf/2007.03875.pdf) arXiv preprint arXiv:2007.03875 (2020).


[Go back to the README](../README.md)
