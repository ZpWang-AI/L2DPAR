# L2DPAR

Coming soon.

## CIKM 2024 Paper

Learning to Differentiate Pairwise-Argument Representations for Implicit Discourse Relation Recognition

[https://doi.org/10.1145/3627673.3679584](https://doi.org/10.1145/3627673.3679584)

## Citation

```
@inproceedings{wangLearningDifferentiatePairwiseArgument2024,
    author = {Wang, Zhipang and Hong, Yu and Lu, Yuxiang and Zhou, Xiabing and Yao, Jianmin and Zhou, Guodong},
    title = {Learning to Differentiate Pairwise-Argument Representations for Implicit Discourse Relation Recognition},
    year = {2024},
    isbn = {9798400704369},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    url = {https://doi.org/10.1145/3627673.3679584},
    doi = {10.1145/3627673.3679584},
    abstract = {Recognizing implicit discourse relations between texts is challenging due to the absence of explicit connectives. Encoding texts into distinguishable semantic representations is beneficial to connective-free relation determination. To enable encoders to produce clearly distinguishable representations, we propose a joint learning framework. It combines prototypical and adversarial learning as well as hub-migration based redistribution. We experiment on PDTB 2.0, PDTB 3.0 and the CoNLL-2016 shared benchmark dataset. Experimental results show that our methods yield substantial improvements, compared to BERT, RoBERTa and DeBERTa baselines. In the separate comparison experiment where implicit connectives are disable during training, our models outperform the previous work for the four main discourse relation types (Temporality, Comparison, Contingency and Expansion), achieving F1-scores of about 60.75\%, 63.48\%, 75.70\% and 77.09\%. On the other hand, our models obtain comparable performance compared to part of the state-of-the-art models which adopt implicit connectives as observable hints for training. When the pretrained language models are used as the backbones, our methods yield the extra time consumption, which is about 1 hour at worst when training is conducted on Tesla 40GB A100 GPU.},
    booktitle = {Proceedings of the 33rd ACM International Conference on Information and Knowledge Management},
    pages = {2503–2512},
    numpages = {10},
    keywords = {adversarial learning, distinguishable representation, hub-migration based redistribution, implicit discourse relation recognition, joint learning framework, prototypical learning},
    location = {Boise, ID, USA},
    series = {CIKM '24}
}
```