
# Play Store App Review Analysis EDA
# Introduction 

This repository contains an Exploratory Data Analysis (EDA) of app reviews from the Google Play Store. The goal of this project is to analyze and gain insights from the reviews provided by users, allowing app developers and stakeholders to understand customer sentiments, identify areas for improvement, and make data-driven decisions.

# Data Summary
1. Play Store App Data

In  given Play store dataset there are total 13 columns and 10841 rows. It contains all the information of different types of applications like name of app, category of app, ratings from the user, size, installs, type of app(free/paid), price of app, content, genres, last updated date, current version of app available on play store and minimum required android version.

2.  User Reviews Data

In this dataset there are 5 columns and 64295 rows. It contains information regarding the reviews given by users, like review, sentiment of that review, sentiment polarity and sentiment subjectivity of that particular reviews.


# Analysis Approach
The EDA process in this project involves the following steps:

* Data Loading and Cleaning : The dataset will be loaded into the analysis environment, and any necessary cleaning steps will be performed, such as handling missing values, removing duplicates, and ensuring data consistency.

* Descriptive Statistics: Initial descriptive statistics will be calculated to provide an overview of the dataset. This includes summary statistics, such as counts, means, medians, and distributions of ratings and review lengths.

* Text Preprocessing: To prepare the review text for analysis, preprocessing techniques such as tokenization, stop word removal, and stemming/lemmatization will be applied. This step aims to transform raw text into a more manageable format for further analysis.

* Sentiment Analysis: Sentiment analysis will be performed to determine the polarity (positive, negative, or neutral) of each review. This analysis will enable us to understand the overall sentiment of the users towards the app and identify any patterns or trends.

* Exploratory Data Visualization: Various visualizations, such as bar plots, word clouds, and scatter plots, will be created to explore the relationships between different variables. These visualizations will help uncover insights and patterns within the data.

* Topic Modeling: Topic modeling techniques, such as Latent Dirichlet Allocation (LDA), will be employed to identify the main topics or themes present in the reviews. This analysis can provide valuable information about the aspects of the app that users frequently discuss.



# Conclusion
By conducting this Play Store App Review Analysis EDA, we aim to provide valuable insights to app developers and stakeholders. Understanding user sentiments, identifying potential improvements, and discovering important topics discussed by users can greatly enhance the app's performance and user satisfaction.
