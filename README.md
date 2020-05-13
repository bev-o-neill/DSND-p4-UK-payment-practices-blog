# UK payment practices analysis

## Installation

The code was developed using Python 3, PySpark v.xxx, Pandas, Numpy and Matplotlib, and Seaborn.

## Project Motivation
Customer churn is a thorny issue for many businesses.  Losing customers means losing revenue. British businesses are losing an eye-watering £25bn per year in avoidable customer churn. 

Sparkify, a fictitious music-streaming company, wants to get a grip on their own customer churn. They've given us access to a sample of their event log database to develop a model for predicting who of their user base is a flight-risk.

## File Descriptions

All analysis and model development is contained in the Jupyter notebook sparkify.ipynb

The dataset used in this Jupyter notebook is mini_sparkify_event_data.json. This data is a sample of the full Sparkify dataset made available by Udacity. The full dataset needs to be accessed and analysed via a Spark cluster deployed on the cloud, which is not in scope for this project. This would be an obvious extension to the work presented here.

## Results

The main findings of this analysis are summarised in a blog post available here: <insert blog link here>

We developed 65 variables. These can be broadly categorised as:
* Time since registration and latest activity
* Subscription level
* Sessions counts
* Interaction counts
* Songs played
* Home/Add Friend/Add to Playlist/Next Song/Thumbs Up/Logout page views
* Days/Weeks/Fortnights active and activity ratios
* Session/interaction/time on site in the weeks 1,2,3,4 prior to latest activity
* Ratio of activity in the final fortnight compared to the fortnight previous.

Model were developed using the PySpark ML library.  The model algorithms we used were: 
* Naive Bayes
* Logistic Regression 
* Gradient Boosted Tree 
* Linear SVM

Model results: 
* Naive Bayes (F1 Score: xxx)
* Logistic Regression (F1 Score: xxx)
* Gradient Boosted Tree (F1 Score: xxx)
* Linear SVM (F1 Score: xxx)

Hyperparameter tuning was run on the Gradient Boosted Tree. Final model results:
* F1 Score: xxx
* Area under the Precision-Recall curve: xxx

## Licensing, Authors, Acknowledgements
Dataset are courtesy of Udacity.

