# ID-SMSA: Indonesian stock market dataset for sentiment analysis

This repository contains datasets related to our paper [ID-SMSA: Indonesian stock market dataset for sentiment analysis](https://doi.org/10.1016/j.dib.2022.108554). This dataset is also available on the [Mendeley Data website](https://doi.org/10.1016/j.dib.2025.111571).

## Value of the Data

- Public stock market datasets are typically in English and focus on foreign stock markets. None of them focus on the Indonesian stock market. ID-SMSA is the first Indonesian stock market dataset presented in Indonesia. Moreover, this high quality, domain specific dataset is annotated for sentiment analysis tasks that supports the research community in learning and understanding Indonesian stock market.
- The dataset contains more than 3000 sentiment tweets (i.e., positive, neutral, negative) related to the Indonesian stock market, mined from X (formerly Twitter) using the top 10 most significant market caps in the Indonesian stock market as the keyword and ranged within the period of January 12, 2021, to March 1, 2024. It is annotated following specific annotation criteria created and reviewed by an expert in clinical psychology.
- ID-SMSA dataset can be utilized for research community such as researchers, developers, stock analysts to analyze the sentiment trends and stock-related discussions and gain insights using existing Natural Language Processing (NLP) models like BERT, LSTM, and Transformer. Thus, it enables the development of sentiment analysis models specifically trained on the Indonesian financial market, contributing to both academic research and real-world financial applications.
- The dataset includes extra attributes and metadata, such as tweet date, quote count, reply count, retweet count, and favorite count. These attributes open the possibilities for broader sentiment analysis research, including market reactions, social media influence, and investor sentiment dynamics overtime. These could improve models for classifying tweet sentiment and may also be helpful for future sentiment analysis research.

## Data Annotation

- Each tweet in the dataset was manually annotated with a single sentiment label: positive, neutral, or negative.

- The annotation process was based on clearly defined sentiment criteria developed by the authors and reviewed by an expert in clinical psychology. These criteria included indicators such as praise, optimism, or good financial news for positive sentiment; disappointment, risk, or negative news for negative sentiment; and factual or sentiment-neutral statements for neutral sentiment.

- Two annotators labeled the tweets independently. Tweets with matching labels were retained, while those with differing labels were excluded to ensure consistency and reduce ambiguity.

- A Cohen’s Kappa score (0.779, indicating substantial agreement) were used to verify inter-annotator reliability.

- Anonymization was applied during preprocessing, replacing sensitive elements like usernames, URLs, and hashtags to protect user privacy.

## List of Attribute

<!-- Change this -->

Although this work focuses on product reviews, other details related to the product review are captured, such as Price, Number Sold, and Total Review. The list of attributes is shown in the Table below.

| Attribute       | Description                                              |
| --------------- | -------------------------------------------------------- |
| Category        | Product classification by category                       |
| Product Name    | Name of the reviewed product                             |
| Location        | City name of the shop or product seller                  |
| Price           | Price in IDR of the reviewed product                     |
| Overall Rating  | Overall product rating                                   |
| Number Sold     | Total number of products sold                            |
| Total Reviews   | Total number of reviews given by the customers           |
| Customer Rating | Product rating (range 1 to 5) from the customers         |
| Customer Review | Product reviews given to the product by the customers    |
| Sentiment       | Sentiment labels (i.e., Positive, Negative)              |
| Emotion         | Emotion labels (i.e., Anger, Fear, Happy, Love, Sadness) |

## Citation

<!-- Change this -->

If you use this dataset in a scientific publication, we would appreciate using the following citations:

### Plain Text

<!-- Change this -->

Sutoyo, R., Achmad, S., Chowanda, A., Andangsari, E. W., & Isa, S. M. (2022). PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks. _Data in Brief_, _44_, 108554.

### BibTeX

<!-- Change this -->

```
@article{SUTOYO2022108554,
title = {PRDECT-ID: Indonesian product reviews dataset for emotions classification tasks},
journal = {Data in Brief},
volume = {44},
pages = {108554},
year = {2022},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2022.108554},
url = {https://www.sciencedirect.com/science/article/pii/S2352340922007612},
author = {Rhio Sutoyo and Said Achmad and Andry Chowanda and Esther Widhi Andangsari and Sani M. Isa},
keywords = {Natural language processing, Text processing, Text mining, Emotions classification, Sentiment analysis},
abstract = {Recognizing emotions is vital in communication. Emotions convey additional meanings to the communication process. Nowadays, people can communicate their emotions on many platforms; one is the product review. Product reviews in the online platform are an important element that affects customers’ buying decisions. Hence, it is essential to recognize emotions from the product reviews. Emotions recognition from the product reviews can be done automatically using a machine or deep learning algorithm. Dataset can be considered as the fuel to model the recognizer. However, only a limited dataset exists in recognizing emotions from the product reviews, particularly in a local language. This research contributes to the dataset collection of 5400 product reviews in Indonesian. It was carefully curated from various (29) product categories, annotated with five emotions, and verified by an expert in clinical psychology. The dataset supports an innovative process to build automatic emotion classification on product reviews.}
}
```

## Poster

<!-- Change this -->

![alt text](https://github.com/rhiosutoyo/PRDECT-ID-Indonesian-Product-Reviews-Dataset/blob/main/Assets/PRDECT-ID_Poster.png?raw=true)
