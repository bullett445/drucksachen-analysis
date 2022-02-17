# Predicting twitter engagement on local politics documents based on the headline

The analysis was carried out following the CRISP-DM process.

The jupyter notebook in this repository demonstrates the prediction of twitter engagement on tweets of the twitter bot @hannoverpolitik in the following steps:
## Business Understanding

The bot is a freelance project without any commercial interest. It is run for the sake of transparency in local politics' proceedings. The analysis for academic interest only.

## Data Understanding

To understanding the data some descriptive analysis is carried out within the notebook. It delivers insights into the types of documents as well as a more detailed view into the engagements happening on the tweets.

## Prepare Data

The headlines of the documents are prepared into a frequency matrix for further analysis. Test data is set aside.

## Data Modeling

A random forest is trained on the training data.

## Evaluate the Results

The quality of the model is evaluated using a confusion matrix as well as the metrics accuracy, precission and recall. Finally feature importance is evaluated to gain some insights into the topic which people engage with.

The notebook was developed in an anaconda installation in its own environment with the following backages
* jupyter
* notebook 
* matplotlib
* numpy
* pandas
* scikit-learn
* sqlite
* seaborn

The data is provided in sqlite3 database. Find the description of the details in the notebook.

The german stopwords collection was taken from: https://github.com/stopwords-iso/stopwords-de under MIT license.

A blogpost about the findings have been published at https://medium.com/@jan.krueger/is-anyone-interested-8f613dda84f2
