# Swedish NLP dataset resources
Here we collect resources for Swedish Text Data.
We are looking for collaborators to add sources and scraped data.

## Raw text datasets

* Swedish wikipedia
Wikipedia is a great resource for high quality text.  
First install tools with ´install-tools.sh´ then run ´./get-data-wiki.sh sv´ and it will download and preprocess the swedish wikipedia data

* Litteraturbanken

* Oscar

## Evaluation datasets

* SUPERLIM

* XNLI for Swedish  
https://github.com/salesforce/xnli_extension  
Translated from English to Swedish with Google Translate  
Paper: `BERT is Not an Interlingua and the Bias of Tokenization` [[1]](#1)

* STS-b for Swedish  
https://github.com/timpal0l/sts-benchmark-swedish  
Translated from English to Swedish with Google Translate  
Paper: `Why Not Simply Translate? A First Swedish Evaluation Benchmark for Semantic Similarity` [[2]](#2) 

* Swedish reviews  
https://github.com/huggingface/datasets/tree/master/datasets/swedish_reviews

## Swedish datasets on huggingface datasets

* There are a lot of Swedish datasets on huggingface datasets

## General Swedish corpora resources

* https://www.ling.su.se/english/nlp/corpora-and-resources
* https://spraakbanken.gu.se/en/resources

## References
<a id="1">[1]</a>  
```
@article{singhMultiLingTokBias2019,
title={{BERT is Not an Interlingua and the Bias of Tokenization}},
author={Singh, Jasdeep and McCann, Bryan and Xiong, Caiming and Socher, Richard},
journal={The Workshop on Deep Learning for Low-Resource NLP at EMNLP 2019},
year={2019}
}
```

<a id="2">[2]</a>
```
@article{isbister2020not,
  title={Why Not Simply Translate? A First Swedish Evaluation Benchmark for Semantic Similarity},
  author={Isbister, Tim and Sahlgren, Magnus},
  journal={arXiv preprint arXiv:2009.03116},
  year={2020}
}
```
