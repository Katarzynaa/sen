# SEN - Sentiment analysis of Entities in News headlines
## How to Cite:

Please cite our [paper](https://www.sciencedirect.com/science/article/pii/S1877050921018755) if you want to use this data 
```
@article{sydow-baraniak-SENdataset-kes2021,
title = {A dataset for Sentiment analysis of Entities in News headlines (SEN)},
journal = {Procedia Computer Science},
volume = {192},
pages = {3627-3636},
year = {2021},
note = {Knowledge-Based and Intelligent Information & Engineering Systems: Proceedings of the 25th International Conference KES2021},
issn = {1877-0509},
doi = {https://doi.org/10.1016/j.procs.2021.09.136},
url = {https://www.sciencedirect.com/science/article/pii/S1877050921018755},
author = {Katarzyna Baraniak and Marcin Sydow},
}
```

## SEN - Description
SEN is a novel publicly available human-labelled dataset for training and testing machine learning algorithms for the problem of entity level sentiment analysis of political news headlines.

On-line news portals play a very important role in the information society. Fair media should present reliable and objective information. In practice there is an observable positive or negative bias concerning named entities (e.g. politicians) mentioned in the on-line news headlines.
Our dataset consists of 3819 human-labelled political news headlines coming from several major on-line media outlets in English and Polish.

Our SEN dataset package consists of 3 files: two for English news (url_en.csv, url_en_amazon.csv) and one for Polish (url_pl.csv).

Each record contains an id, news url, a named entity mentioned in the headline and a human annotated label (one of “positive”, “neutral”, “negative” ). 

News url enables to access the page of news articles and dowload the news headline that annotation is for. Due to copyrights no headlines are provided.


Each headline-entity pair was annotated via team of volunteer researchers (the whole SEN-pl dataset and a subset of 1271 English records: the url_en.csv and url_pl.csv) or via the Amazon Mechanical Turk service (a subset of 1360 English records: url_en_amazon.csv).

Details of the process of preparing the dataset and presenting its analysis are presented in the [paper](https://www.sciencedirect.com/science/article/pii/S1877050921018755).
In case of any questions, please contact one of the authors.


For reaserch purposes, you can find this dataset also [here](https://zenodo.org/record/5211931). There you can find also separate version of dataset without outliers.
