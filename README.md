# Twitter-SentimentAnalysis
This script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event 

![Twitter-Sentiment-Analysis](twitter-sentiment-analysis.png)

# Getting Started

First of all login from your Twitter account and goto [Twitter Apps](https://apps.twitter.com/). Create a new app ([How to create twitter app](http://www.letscodepro.com/twitter-sentiment-analysis/)) and goto __Keys and access tokens__ and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later. 

# Installation
```
pip install tweepy
```
```
pip install matplotlib
```
```
pip install textblob
```
[setup.py](https://github.com/harunshimanto/Twitter-SentimentAnalysis/blob/master/setup.py)

### Usage

Once you have created an app on twitter and installed all the dependencies  by running __setup.py__, open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script. You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.

## Built With

* Python 3.6
* tweepy
* textblob
* matplotlib

## Contributing

1. Fork it
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## Authors
Harun Shimanto  

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/harunshimanto/Twitter-SentimentAnalysis/blob/master/LICENSE) file for details
