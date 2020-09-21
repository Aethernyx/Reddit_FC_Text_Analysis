# Reddit_FC_Text_Analysis

In this repository, I take a look at text data in the NYCFC subreddit. Using the praw in tandem with the reddit API, I scraped thread title, thread comments, and comment date+times for the top 100 threads under the 'Merch' flair.


![image_of_reddit_page](/images/nycfc_reddit.png)

## Dependencies
- Python 3.6
- Tensorflow
- Keras
- Scikit-Learn
- Praw
- Pandas
- Matplotlib
- Seaborn
- Numpy
- tqdm
- os
- datetime
- google.colab
- re
- requests
- Reddit API Credentials

## Results of Model Prediction
![image_of_graph](/images/Sentiment_Countplot.png)


The image above shows the counts for each sentiment of each post in the 32 threads on the NYCFC subreddit. The x-axis contains thread id's which correspond to each of the threads I have scraped data for.

From the analysis above it looks like people are speaking positively of the leaked away kit, and pins. It looks like they enjoy swapping pins with each other. Maybe that's something that can be built upon - for example maybe the club can make a number of different exclusive pins, or hold events where people can trade exclusive pins with each other as a promotional tool.
