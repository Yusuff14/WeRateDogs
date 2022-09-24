# WeRateDogs Twitter Page
## by Yusuff Adebayo
### Introduction
WeRateDogs is an awesome Twitter page that rates people's dogs with a humorous comment about the dog. Usually, the ratings are above normal scale of 10 and can even be higher than 15.
According to the founder, Matt Nelson, WeRateDogs community is on a mission to celebrate good dogs (they’re all good dogs) by sharing their stories, improving their lives, and helping the ones who need us most.

This project majorly involves data wrangling especially dealing with both the quality and tidiness issues in the data. During this process, three different data on WeRateDogs were gathered using the necessary libraries, assessed manually and programmatically, cleaned both the dirty and messy data, and analyzed statistically and visually. One of the data used was gotten by querying Twitter API since additional data was needed for this analysis. 

### Datasets
The three data and the approaches involved are:

1. **The WeRateDog Twitter archive:** This data (twitter-archive-enhanced.csv) was available on hand and thereby downloaded manually before being uploaded into Jupyter Notebook and read into DataFrame.

2. **The tweet image predictions:** This file (subsequently stored as tweet_image_predictions.tsv) is hosted on Udacity's servers and was downloaded programmatically using the Requests library . It contains the modeling outcome of each image using Neural Network.

3. **The Tweet_json data:** This was created after querying the Twitter API for additional data such as favorite count, retweet count etc. These additional data were scraped from Twitter, read line by line before it was later stored as 'tweet_json.txt'.

### Key Insights
The insights generated at the end of wrangling process include but not limited to the following:
1. Statistical Distribution of WeRateDog Data.
2. Most Frequent Dog Stage.
3. Ratings Distribution between Pupper and Floofer.
4. Relationship between Ratings and People's Engagement.

The sneak peek of this analysis can be found [here](https://yusuff14.github.io/WeRateDogs/).
