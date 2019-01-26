# TEXT-MINING-FOR-IMDB-REVIEWS
IMDB, Internet Movie database is an online database of information related to word films, television programs, etc. with fan reviews and ratings. This site is extremely well-known among movie fanatics. The dataset is the labeled dataset of 50,000 IMDB reviews, which has binary sentiment. It means that IMDB rating less than 5 results in a sentiment score of 0 and IMDB rating no less than 7 have a sentiment score of 0. 

The main purpose of this project is to put forward an overview of the words used in movie reviews and help audience to compare the common and distinct features of those reviews. Under examining this dataset, we could have a basic understanding of data mining for transforming the unstructured text in to structured data for use in further analysis and how it can be applied to different fields such as social network comments or book reviews. More importantly, data mining is the basis for Natural Language Processing (NLP) and both are the integral part of machine learning algorithm.

The process of text mining for this IMDB reviews includes:
-	Giving the overview of the prevalent words with bar graphs and word cloud.
-	Comparing positive and negative reviews based on common and different words between two sentiments using commonality cloud and comparison cloud respectively.
-	Giving a different insight into common words between two sentiments by using pyramid plot.
-	Finding cluster of words in sentiment 1 by using hierarchical clustering.
-	Plotting the association for a specific word in sentiment 1.

However, because of the scope of this project and limitation in time and knowledge, there are some paths of development for this project that need to be taken into consideration:
-	Developing an R Shiny application which users can exclude some undesirable words and choose the targeted words to examine as well as choosing the number of trees cut.
-	Factoring in word stemming, which means consolidating the different words with the same meaning (for example: work/working/works/workers).
-	Expanding word analysis for two or more words or even a whole sentence, not limiting to single word.
-	Giving an insight into predictive analytics, which means conjecture the attitude of a reviews based on written words
