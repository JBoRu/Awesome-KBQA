# Large-scale Complex Question Answering

LC-QuAD v1.0 and v2.0 are large-scale QA datasets towards complex questions against knowledge graphs. 

### Table of contents

- [LC-QuAD 1.0](#lc-quad-v1)
- [LC-QuAD 2.0](#lc-quad-v2)
  
  
## LC-QuAD v1

The Largescale Complex Question Answering Dataset 1.0 (LC-QuAD 1.0)<sup>[[1]](#myfootnote1)</sup> is a Question Answering dataset with 5000 pairs of question and its corresponding SPARQL query. The target knowledge base is DBpedia, specifically, the April, 2016 version. 
Please see the original [paper](http://lc-quad.sda.tech/static/ISWC2017_paper_152.pdf) for details about the dataset creation process and framework.

This dataset can be downloaded via the [link](https://github.com/AskNowQA/LC-QuAD).

### Leaderboard

| Year | Type | F1  | Acc |        Reported by      | Official Repo |
|:----:|:----:|:---:|:---:|:-----------------------:|:-------------:|
| 2021 |  SP-based  |71.8|  -   |  [Zheng et. al.](https://dl.acm.org/doi/abs/10.1145/3459637.3482235) | - |
| 2020 |  SP-based  |74.8|  -   |  [Chen et. al.](https://www.ijcai.org/proceedings/2020/0519.pdf) | [Repo](https://github.com/Bahuia/AQGNet) |
| 2019 |  IR-based  |33.0|  -   |  [Zheng et. al.](https://arxiv.org/pdf/1908.06917.pdf) | [Repo](https://github.com/svakulenk0/KBQA?utm_source=catalyzex.com) |
| 2018 |  SP-based  |75.0|  -   |  [Zafar et. al.](http://jens-lehmann.org/files/2018/eswc_qa_query_generation.pdf) | [Repo](https://github.com/AskNowQA/SQG) |


## LC-QuAD v2

The Largescale Complex Question Answering Dataset 2.0 (LC-QuAD 2.0)<sup>[[2]](#myfootnote2)</sup> is a Large Question Answering dataset with 30,000 pairs of question 
and its corresponding SPARQL query. The target knowledge base is [Wikidata](https://wikidata.org/wiki/Wikidata:Main_Page/) and [DBpedia](https://dbpedia.org/), specifically the 2018 version. 
Please see our [paper](https://figshare.com/projects/LCQuAD_2_0/62270) for details about the dataset creation process and framework.

This dataset can be downloaded via the [link](https://figshare.com/projects/LCQuAD_2_0/62270).

### Leaderboard

| Year | Type | F1  | Acc |        Reported by      | Official Repo |
|:----:|:----:|:---:|:---:|:-----------------------:|:-------------:|


## References
<a name="myfootnote1">[1]</a> Trivedi, Priyansh, Gaurav Maheshwari, Mohnish Dubey, and Jens Lehmann. [Lc-quad: A corpus for complex question answering over knowledge graphs.](http://lc-quad.sda.tech/static/ISWC2017_paper_152.pdf) In International Semantic Web Conference, pp. 210-218. Springer, Cham, 2017.

<a name="myfootnote2">[2]</a> Dubey, Mohnish, Debayan Banerjee, Abdelrahman Abdelkawi, and Jens Lehmann. [Lc-quad 2.0: A large dataset for complex question answering over wikidata and dbpedia.](http://jens-lehmann.org/files/2019/iswc_lcquad2.pdf) In International semantic web conference, pp. 69-78. Springer, Cham, 2019.


[Go back to the README](../README.md)
