## Analysis of social media conversations surrounding COVID-19 in Singapore

The following files were used to analyse Facebook, Reddit and Twitter data collected from January 2020 to March 2020. As more data is collected, the code serves as a template to conduct further analysis.
Analysis conducted include:
- Topic modelling to identify key topics and user groups in Singapore’s social media scene
- Sentiment analysis to model and evaluate netizen sentiments based on social media posts, against the growth of COVID-19 cases in Singapore
- Social network analysis to model the Twitter retweet network in Singapore on posts related to COVID-19


A summary of the analysis results can be found [here](https://drive.google.com/file/d/1cW87FL6o7GIipHZEP8raWf4pfGQGxRnm/view).

### Brief summary of each file

#### ***Twitter Data Cleaning & Preprocessing.ipynb***
- Text pre-processing for Twitter data collected using the Twitter REST API

#### ***Retrieve Singapore Tweets For Analysis.ipynb***
- With data collected using Twitter REST API, filter tweets with location tag "SG" for analysis
   
#### ***Topic modelling - Twitter.ipynb***
- Conduct topic modelling (Latent Dirichlet Allocation) on data collected using Twitter REST API

#### ***Sentiment Analysis - Twitter .ipynb***
- Conduct sentiment analysis on Twitter data using [VADER](https://github.com/cjhutto/vaderSentiment)

#### Extract Twitter Network.ipynb
- Extract Twitter retweet network in Singapore, for network analysis to be conducted (exports a gml file for visualisation on Gephi)

#### ***Topic Modelling - Reddit.ipynb***
- Conduct topic modelling (Latent Dirichlet Allocation) on data collected from Reddit API

#### ***Sentiment Analysis - Reddit.ipynb***
- Conduct sentiment analysis on Reddit data using [VADER](https://github.com/cjhutto/vaderSentiment)

#### ***Number of Facebook Posts Against Time.ipynb***
- Plot the number of Facebook posts against time for key ministers (of Singapore government) involved in COVID-19 response
