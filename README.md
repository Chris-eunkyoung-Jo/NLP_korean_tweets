# NLP_korean_tweets

# NLP_korean_tweets


This is the code and material I used completing my master's thesis, called Studying Online Public Debate on Freedom of the Press in South Korea: Natural Language Processing of Tweets. I scraped from Twitter, obtained a 70,111 tweets dataset, and then carried out three NLP tasks: keyword extraction with Term Frequency-Inverse Document Frequency (TF-IDF), topic modeling with Latent Dirichlet Allocation (LDA), and clustering with K-means.
For scraping tweets I used the module snscrape https://github.com/JustAnotherArchivist/snscrape, and for tokenizing the dataset, the KoNLPy option okt.nouns https://konlpy.org/en/latest/.
The tweets were scraped by keyword combinations related to freedom of the press in South Korea.
