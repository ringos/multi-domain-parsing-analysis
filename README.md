# Challenges to Open-Domain Constituency Parsing

This repo contains the data and the parsed outputs for the paper "Challenges to Open-Domain Constituency Parsing" in *the Findings of ACL 2022*.

## MCTB
We release MCTB_en, which contains test-sets for five domains, including dialogue, forum, law, literature and review, with 1,000 instances per domain. 
The data can be found in `data/MCTB_en`. 
We are also planning to release a Chinese multi-domain test treebank in the future. 


## Parsed_outputs
We release the parsed outputs of various treebanks, decoded by [the in-order transition-based parser](https://github.com/LeonCrashCode/InOrderParser) and [the re-implemented BERT-augmented version](https://github.com/dpfried/rnng-bert).
The parsed outputs can be found in `data/parsed_outputs`.

## Acknowledgements
We thank the authors of [BLLIP](https://github.com/BLLIP/bllip-parser), [the in-order transition-based parser](https://github.com/LeonCrashCode/InOrderParser), [rnng-bert](https://github.com/dpfried/rnng-bert) and [self-attentive parser](https://github.com/nikitakit/self-attentive-parser) for sharing their code and model checkpoints. 

## Cite
```
@inproceedings{crossdomain-parsing-analysis,
  author = {Sen Yang and Leyang Cui and Ruoxi Ning and Di Wu and Yue Zhang},
  title = {Challenges to Open-Domain Constituency Parsing},
  booktitle = {Findings of ACL},
  year = {2022},
} 


