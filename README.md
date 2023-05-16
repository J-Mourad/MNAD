# About the MNAD Dataset
The MNAD corpus is a collection of over **1 million Moroccan news articles** written in modern Arabic language. These news articles have been gathered from 11 prominent electronic news sources. The dataset is made available to the academic community for research purposes, such as data mining (clustering, classification, etc.), information retrieval (ranking, search, etc.), and other non-commercial activities.

## Dataset Fields
- Title: The title of the article
- Body: The body of the article
- Category: The category of the article
- Source: The Electronic News paper source of the article

## About Version 1 of the Dataset (MNAD.v1)
Version 1 of the dataset comprises 418,563 articles classified into 19 categories. The data was collected from well-known electronic news sources, namely Akhbarona.ma, Hespress.ma, Hibapress.com, and Le360.com. The articles were stored in four separate CSV files, each corresponding to the news website source. Each CSV file contains three fields: Title, Body, and Category of the news article.

The dataset is rich in Arabic vocabulary, with approximately 906,125 unique words. It has been utilized as a benchmark in the research paper:
```"A Moroccan News Articles Dataset (MNAD) For Arabic Text Categorization". In 2021 International Conference on Decision Aid Sciences and Application (DASA).```

This dataset is available for download from the following sources:
- Kaggle Datasets : [MNADv1](https://www.kaggle.com/datasets/jmourad100/mnad-moroccan-news-articles-dataset)
- Huggingface Datasets: [MNADv1](https://huggingface.co/datasets/J-Mourad/MNAD.v1)

## About Version 2 of the Dataset (MNAD.v2)
Version 2 of the MNAD dataset includes an additional 653,901 articles, bringing the total number of articles to over 1 million (1,069,489), classified into the same 19 categories as in version 1. The new documents were collected from seven additional prominent Moroccan news websites, namely al3omk.com, medi1news.com, alayam24.com, anfaspress.com, alyaoum24.com, barlamane.com, and SnrtNews.com.

The newly collected articles have been merged with the articles from the previous version into a single CSV file named ```MNADv2.csv```. This file includes an additional column called "Source" to indicate the source of each news article.

Furthermore, MNAD.v2 incorporates improved pre-processing techniques and data cleaning methods. These enhancements involve removing duplicates, eliminating multiple spaces, discarding rows with NaN values, replacing new lines with "\n", excluding very long and very short articles, and removing non-Arabic articles. These additions and improvements aim to enhance the usability and value of the MNAD dataset for researchers and practitioners in the field of Arabic text analysis.

This dataset is available for download from the following sources:
- Kaggle Datasets : [MNADv2](https://huggingface.co/datasets/J-Mourad/MNAD.v2)
- Huggingface Datasets: [MNADv2](https://huggingface.co/datasets/J-Mourad/MNAD.v2)

## Citation
If you use our data, please cite the following paper:

```bibtex
@inproceedings{MNAD2021,
    author    = {Mourad Jbene and 
                 Smail Tigani and 
                 Rachid Saadane and 
                 Abdellah Chehri},
    title     = {A Moroccan News Articles Dataset ({MNAD}) For Arabic Text Categorization},
    year      = {2021},
    publisher = {{IEEE}},
    booktitle = {2021 International Conference on Decision Aid Sciences and Application ({DASA})}
    doi       = {10.1109/dasa53625.2021.9682402},
    url       = {https://doi.org/10.1109/dasa53625.2021.9682402},
}
```
