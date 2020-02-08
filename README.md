# Tweet-Summarizer

Objective:  

To build Tweet Summarizer, which is an algorithm that summarizes the most
widely discussed topics on Twitter. It gives a short summary of what’s trending
on the internet which includes hashtags, and other popular topics. Summaries
serve the purpose of helping the user in understanding “why the topic is
trending”.

Methodology:

1. Take tweets as an input from trending topics on Twitter.
2. Tweepy library is used to access the Twitter API. 
3. Refine the data. Refining includes removing stop words, tokenizing each word,
and stemming.
4. Refined data is processed. Processing includes finding Similarity, and doing
Latent Semantic Analysis(LSA).
5. After the data is processed, the algorithm prints the summary of the relevant
information, using the processed data.
