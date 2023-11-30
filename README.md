# Sentiment-Analysis-on-Russia-Ukraine-War-tweets
Sentiment Analysis on 500 Tweets about the Russia-Ukraine War

**Introduction**

The Russo-Ukrainian conflict escalated in February 2022 after Russia recognised two Ukrainian breakaway regions - the Donetsk People’s Republic and the Luhansk People’s Republic. On 21 February 2022, Russia officially recognised the two self-proclaimed separatist states in the Donbas, and sent troops to the territories. 
People around the world have different opinions on the war. There are people who support Ukraine while there are also people who agree with Russia’s decision on going to war. So, by using the tweets on Twitter, I am going to understand people’s sentiments on Russia going to war against Ukraine and as to what the majority of people support and in order to do this, I will use Sentiment Analysis and Topic Modeling to discover the latent topics of an unstructured collection of documents and organize the collection according to the discovered topics.

**Dataset Description**

Data was collected from Twitter. I found the tweets on Twitter which are related to the Russia - Ukraine war and analyzed them. The data was collected mainly from the following hashtags - #SaveUkraine, #JusticeForUkraine, #UkraineRussiaWar, #RussiaUkraineConflict.  I have collected the data in the dates between 2022-08-05 and 2022-12-23. I collected 500 tweets in English language, from each hashtag and merged all the datasets into one dataframe. I cleaned the data by removing any hyperlinks and using stopwords, after which I analyze and answer the research questions, using Sentiment Intensity Analyzer to compare the polarity scores of different tweets into three categories - positive, negative and neutral.

**Conclusion**

The results of Sentiment Analysis reveal that most of the people have a negative sentiment toward the war.  By the results of LDA, we can clearly notice that most people have positive sentiments towards Ukraine and negative sentiments towards Russia.


