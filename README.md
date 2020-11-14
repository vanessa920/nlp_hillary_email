# Inside Hillary Clinton's Emails

Throughout 2015, Hillary Clinton has been embroiled in controversy over the use of personal email accounts on non-government servers during her time as the United States Secretary of State. Some political experts and opponents maintain that Clinton's use of personal email accounts to conduct Secretary of State affairs is in violation of protocols and federal laws that ensure appropriate recordkeeping of government activity. Hillary's campaign has provided their own four sentence summary of her email use here.

There have been a number of Freedom of Information lawsuits filed over the State Department's failure to fully release the emails sent and received on Clinton's private accounts. On Monday, August 31, the State Department released nearly 7,000 pages of Clinton's heavily redacted emails (its biggest release of emails to date).

The documents were released by the State Department as PDFs. Kaggle cleaned and normalized the released documents and are hosting them for public analysis. I focused on the Emails that sent by Hillary Clinton. [Kaggle Dataset](https://www.kaggle.com/kaggle/hillary-clinton-emails)

***

## NLP Methodology

1. Text Preprocessing: Regex text cleaning, Tokenization, Lemmentization and text vectorization with TF-IDF [Text Pre-processing](https://github.com/vanessa920/nlp_hillary_email/blob/main/hillary_email_text_preprocess.ipynb)

2. Topic Modeling: pyLDA, CorEx, K-Mean Cluster, Gensim Word2Vec [Topic Modeling](https://github.com/vanessa920/nlp_hillary_email/blob/main/hillary_sent_nlp.ipynb)

3. Use SQLite create new tabless to explore Hillary's network [Hillary's Network](https://github.com/vanessa920/nlp_hillary_email/blob/main/hillary_network.ipynb)

4. Further EDA to find three topics with pyLDA and Sentiment Analysis using NLTK Vader and TextBlob to conduct Sentiment Analysis [Topic Modeling and Sentiment Analysis Combined](https://github.com/vanessa920/nlp_hillary_email/blob/main/hillary_email_EDA.ipynb

5. Use Tableau for visualization and tell a good story [Tableau Story]: https://public.tableau.com/profile/vanessa.hu#!/vizhome/hilary_email_sentiment/EmailsSentbyHillary


## Key Take Aways


