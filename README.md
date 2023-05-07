# Wrangle-and-Analyse-data-from-Twitter-page

This project was developed to analyse tweets from the [WeRateDogs](https://twitter.com/dog_rates) page from Twitter. It aims to go through the role process of data wrangling: gather, access and clean data.

## Packages

The project requires the installation of the following packages: `Pandas`, `Numpy`, `Matplotlib`, `Seaborn`, `Requests`, `Tweepy`, `Json`, `Datetime` and the magic function `%Matplotlib inline`.

## Datasets

Data was extracted from Udacity's database and 2 datasets will be analyzed: the WeRateDogs Twitter archive ('twitter-archive-enhanced.csv' file) and the tweet image predictions ('image-predictions.tsv' file). Tweets data in json extension was downloaded using the `Tweepy` library and stored in a file called "tweet_json.txt".

![Mediterranean Camera Company](https://github.com/moaazelsokary/Wrangle-and-Analyse-data-from-Twitter-page/blob/main/act_report.pdf)

Real-world data rarely comes clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. we will document our wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries).

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
