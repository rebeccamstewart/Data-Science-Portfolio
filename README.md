# Data-Science-Portfolio

### Twitter Binary Classification with MLs and NNs

The first project added to this portfolio concerns a binary classification problem, specifically, building ML and NN models that can predict the political affiliation (Democrat or Republican) of twitter users based on their tweets.

The motivation behind the creation of this independent project was to gain experience with three areas: 

1.	NLP techniques like Bag-of-words, TFIDF, GloVe, N-Grams, and POS (Part-Of-Speech) tagging.

2.	Building models for text data when represented as sparse matrices or vectors. 

3.	Using the Twitter API, [Tweepy](https://www.tweepy.org/), which can be used to pull tweets using various criteria.

### Political Tweets - Data (and Sentiment) Analysis

The second project also uses the custom twitter objects to pull political tweets for the Gang of Eight (equal parts Democrat and Republican) so that we can assign sentiment to each and analyze the difference between groups of data.

The motivation behind the creation of this independent project was to gain experience with the following areas:

1.	NLP techniques like Pre-Processing, Bag-of-words, etc.

2.	Feature engineering, including Sentiment using [VADER](https://github.com/cjhutto/vaderSentiment) (Valence Aware Dictionary and sEntiment Reasoner).

3.	Explore and analyze the data using various types of visualizations, like word clouds and graphs.

4.	Perform statistical test to see if the difference in sentiment between two groups (Democrat and Republican) are statistically significant

### Fraud Detection Kaggle Competition 

The third project is my first involvement in a [Kaggle competition](https://www.kaggle.com/c/ieee-fraud-detection), but after the competition closed. 

My motivation for working on this Kaggle project included the following:

* Work on a large tabular dataset similar to the one used for a WIDS Kaggle competition that I was anticipating working on in January/February of 2020.

* Gain experience working with a large dataset, at least one that exceeds the size of the ones I was exposed to in an academic setting. As I anticipated, working with large number of features and rows proved challenging in the following areas:

* Figure out tricks that allow one to focus on important features.
  1.	Manage computer memory issues.
  2.	Employ techniques to test changes in the data for optimal model performance without running the entire dataset through a pipeline every single time.

### WiDS Datathon 2020 

The forth project is a result of my first involvement in a live [Kaggle competition](https://www.kaggle.com/c/widsdatathon2020/data).  After joining the local chapter of *Women in Data Science*, [data circles – formerly SeaWids]( https://datacircles.org/) and attending several meet-ups and lectures, I decided to participate in this datathon as part of a group. 

Weekly meetings, along with both collaborative and independent work, led to the production of the Jupyter notebook posted here. This represents only one of the many models and kernels that led to several submissions to the WiDS datathon Kaggle competition. 

### Artificial Neural Network Implemented From Scratch

The fifth project resulted from one of the more difficult assignments given to me near the end of my [Data Science Certificate Program](https://www.pce.uw.edu/certificates/data-science) at the *University of Washington*. We were given the code for a simple Perceptron Model and tasked with the challenge of converting it to a multi-layer Neural Network, configurable with the following parameters;
1. Learning Rate
2. Number of epochs
3. Depth of architecture—number of hidden layers between the input and output layers
4. Number of nodes in a hidden layer—width of the hidden layers  

This classifier was tested using a Red/White Wine Dataset.
