# Challenges to Open-Domain Constituency Parsing



This repo contains the data and the parsed outputs for the paper "Challenges to Open-Domain Constituency Parsing" in *the Findings of ACL 2022*.


## MCTB
We release MCTB_en, which contains test-sets for five domains, including dialogue, forum, law, literature and review, with 1,000 instances per domain. 
The data can be found in `./data/MCTB_en`. 
We are also planning to release a Chinese multi-domain test treebank in the future. 


## Parsed_outputs
The parsed outputs of various treebanks is released. They are decoded by [the in-order transition-based parser](https://github.com/LeonCrashCode/InOrderParser) and [the re-implemented BERT-augmented version](https://github.com/dpfried/rnng-bert).
The parsed outputs can be found in `./data/parsed_outputs`.



### Update: Chinese Data Released
* MCTB_zh is released, along with the parsed outputs from multiple parsers. MCTB_zh covers five domains: 1) biomedical, 2) item description of Taobao products, 3) law, 4) traditional Chinese medicine and 5) web fiction. MCTB_zh data is located in `./data/MCTB_zh`. 

* More details about MCTB_zh can be found in the paper draft which is in `./files/`. The draft is written in Chinese. The main take-away is that: unlike English cross-domain parsing, which is more correlated with the variations of grammar structures rather than those of words, Chinese parsing cares about both of them. This might result from the fact that Chinese has a much larger set of basic elements (i.e., characters), which can not be tokenized into sub-tokens as how English is processed.

---

## Cite
If you use our data, please consider citing the following work:
```
@inproceedings{yang-etal-2022-challenges,
    title = "Challenges to Open-Domain Constituency Parsing",
    author = "Yang, Sen  and
      Cui, Leyang  and
      Ning, Ruoxi  and
      Wu, Di  and
      Zhang, Yue",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2022",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-acl.11",
    doi = "10.18653/v1/2022.findings-acl.11",
    pages = "112--127",
}
```

---

## Acknowledgements
We thank the authors of [BLLIP](https://github.com/BLLIP/bllip-parser), [the in-order transition-based parser](https://github.com/LeonCrashCode/InOrderParser), [rnng-bert](https://github.com/dpfried/rnng-bert) and [self-attentive parser](https://github.com/nikitakit/self-attentive-parser) for sharing their code and model checkpoints. 
