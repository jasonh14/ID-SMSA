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

This dataset focuses on Indonesian stock market discussions extracted from X (formerly Twitter). Each tweet is labeled for sentiment analysis, and additional metadata is included to support deeper insights such as virality and timing. The list of attributes is shown in the table below.

| Attribute      | Description                                  |
| -------------- | -------------------------------------------- |
| Tweet Date     | The date and time when the tweet was created |
| Sentence       | The complete text content of the tweet       |
| Quote Count    | Number of times the tweet has been quoted    |
| Reply Count    | Number of replies the tweet has received     |
| Retweet Count  | Number of times the tweet has been retweeted |
| Favorite Count | Number of times the tweet has been liked     |
| Sentiment      | Total number of products sold                |

## Citation

<!-- Change this -->

If you use this dataset in a scientific publication, we would appreciate using the following citations:

### Plain Text

<!-- Change this -->

Hartanto, J., Liundi, T., Sutoyo, R., & Andangsari, E. W. (2025). ID-SMSA: Indonesian stock market dataset for sentiment analysis. _Data in Brief_, 60, 111571.

### BibTeX

<!-- Change this -->

```
@article{HARTANTO2025111571,
title = {ID-SMSA: Indonesian stock market dataset for sentiment analysis},
journal = {Data in Brief},
volume = {60},
pages = {111571},
year = {2025},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2025.111571},
url = {https://www.sciencedirect.com/science/article/pii/S2352340925003038},
author = {Jason Hartanto and Timothy Liundi and Rhio Sutoyo and Esther Widhi Andangsari},
keywords = {Stock market, Natural language processing, Text processing, Text mining, Sentiment analysis},
abstract = {Social media has impacted daily life, affecting people’s habits regarding accessing and sharing information. Among the platforms, X (formerly Twitter) gives users the freedom of speech to express their subjects and topics. Hence, users express their opinions on every topic, from light-hearted to heavy topics such as politics and the economy. This vast opinion from users creates a valuable resource for research. This paper presents the Indonesian Stock Market Dataset for Sentiment Analysis (ID-SMSA), a collection of 3288 tweets discussing the top 10 largest market caps in the Indonesian stock market as of March 2023. The dataset is in Indonesian and an English translated version is provided, making it the first Indonesian-language dataset discussing the Indonesian stock market. Human annotators labelled each tweet as positive, neutral, or negative based on baseline annotation characteristics criteria created and reviewed by an expert in clinical psychology. A voting system determines which tweets to include in the dataset. This creates a consistent dataset that reflects clear and agreed-upon sentiments and removes ambiguous and contradictory data. The voted tweets include 2339 positive, 999 neutral, and 1025 negative sentiments. This dataset supports research into Indonesian stock market growth and the role of social media in financial discussions.}
}
```

## Poster

<!-- Change this -->

![alt text](https://github.com/jasonh14/ID-SMSA/blob/main/Asset/ID-SMSA_Paper_Poster.png?raw=true)
