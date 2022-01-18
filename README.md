# CogALex 2.0

## Description

This folder contains all results and scripts used to obtain the CogALex 2.0 results.

* CogALex 1.0 contains the original dataset.

* CogALex 2.0 contains the manually modified dataset.

`./results` contains the the averaged results over multiple runs with each model and different combinations of data and all of the jupyter Notebooks used for running the tests. 

The training, evaluation and analysis notebooks can be found at the root of this folder.

## Reference and Paper
Our [paper](https://datacentricai.org/papers/164_CameraReady_CogALex_2_0.pdf) describing the improved dataset and the resulting differences in model-performance were presented at the [Data Centric AI Workshop](https://datacentricai.org) at NeurIPS 2021 

Lang, C., Wachowiak, L., Heinisch, B., & Gromann, D. (2021). *CogALex 2.0: Impact of Data Quality on Lexical-Semantic Relation Prediction*. Data-Centric AI Workshop. 

## Abstract

Predicting lexical-semantic relations between word pairs has successfully been accomplished by pre-trained neural language models. An XLM-RoBERTa-based approach, for instance, achieved the best performance differentiating between hypernymy, synonymy, antonymy, and random relations in four languages in the CogALex-VI 2020 shared task. However, the results also revealed strong performance divergences between languages and confusions of specific relations, especially hypernymy and synonymy. Upon inspection, a difference in data quality across languages and relations could be observed. Thus, we provide a manually improved dataset for lexical-semantic relation prediction and evaluate its impact across three pre-trained neural language models.
