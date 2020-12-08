# Unit 12_NLP

![NLP](https://github.com/amanafzali/Bootcamp_NLP/blob/main/pictures/NLP.jpg?raw=true)

# Tales from the Crypto

In this assignment, I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The following tasks were completed:

1. Sentiment Analysis
2. Natural Language Processing
3. Named Entity Recognition

## Sentiment Analysis

I Used the newsapi to pull the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin.

The following questions were answered performing this analysis.

Q: Which coin had the highest mean positive score?

A: Ethereum

Q: Which coin had the highest compound score?

A: Ethereum has higher compound score however at 50% Bitcoin is highter.

Q. Which coin had the highest positive score?

A: Ethereum

## Natural Language Processing

I used NLTK and Python to tokenize the text for each coin and following tasks were performed.

- Lowercased each word
- Removed punctuation
- Removed stop words

Then I have looked at the ngrams and word frequency for each coin.

- Used NLTK to produce the ngrams for N = 2.
- Listed the top 10 words for each coin.

Finally, I generate word clouds for each coin to summarize the news for each coin.

![btc_wc](https://github.com/amanafzali/Bootcamp_NLP/blob/main/pictures/Bitcoin%20WC.PNG?raw=true)


![eth_wc](https://github.com/amanafzali/Bootcamp_NLP/blob/main/pictures/Ethereum%20WC.PNG?raw=true)



## Named Entity Recognition

In this section, I built a named entity recognition model for both coins and visualized the tags using SpaCy.

![btc_ner](https://github.com/amanafzali/Bootcamp_NLP/blob/main/pictures/Bitcoin%20NER.PNG?raw=true)


![eth_ner](https://github.com/amanafzali/Bootcamp_NLP/blob/main/pictures/Ethereum%20NER.PNG?raw=true)
