<img src="https://media.licdn.com/dms/image/C5616AQEgZnqFKt-mBw/profile-displaybackgroundimage-shrink_350_1400/0?e=1538611200&v=beta&t=hx4FuWn8hmXwI6-8AXDwfuiVbNwjqHbrsTWUJYYCrQU">

# Data Science Portfolio

Welcome! This repository is a portfolio containing several Data Science projects showcasing, but not limited to:
- Data Acquisition via API's and web Scraping.
- Data Analysis
- Data Visualization
- Data Engineering
- Supervised Machine Learning Models | Regression & Classification
- Natural Language Processing (NLP)
- and more!


## Table of Contents

- [Financial Modeling: Forecasting the Stock Market](#FM)
- [Forecasting the West Nile Virus](#WNV)
- [Political Classifier: Classifying Politics Based on News Titles on Reddit](#Politics)


## Project Overview

<a class="anchor" id="FM"></a>

### [Financial Modeling: Forecasting the Stock Market](https://github.com/adam-delreal/Portfolio/tree/master/Financial_Modeling)

Programmed a supervised machine learning models to forecast securities using quantitative technical indicators such as historical stock prices and qualitative data (filing reports) from the United States Securities & Exchange Commission (SEC).

**Tools:** 
[Python](https://www.python.org/) • [Jupyter Notebook/Lab](http://jupyter.org/index.html) • [Seaborn](https://seaborn.pydata.org/introduction.html) • [Matplotlib](https://matplotlib.org/) • [Numpy](http://www.numpy.org/) • [Pandas](https://pandas.pydata.org/) • [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) • [Quandle](https://www.quandl.com/) • [Scikit Learn](http://scikit-learn.org/stable/index.html#) • [Facebook Prophet](https://research.fb.com/prophet-forecasting-at-scale/)

**Data Acquisition:**  
[Quandle's API](https://www.quandl.com/) • [SEC Website](https://www.sec.gov/)

**Exploratory Data Analysis:**
Data Visualization • Visualizing Trends | Visualizing Document Frequency
[Data Engineering](https://github.com/adam-delreal/Portfolio/blob/master/Financial_Modeling/1_Predicting_Stock_Prices/1_EDA.ipynb) • Simple Moving Averages (SMA) | Exponential Moving Averages (EMA) | Percentage Difference per Time Periods | One-Hot Encoding | Time Shifting

**Machine Learning Models:**
Linear Regression Models • Facebook Prophet | Ordinary Least Squares | Random Forest Regressor | Bagging Regressor 

Classification Models • Random Forest Classifier

**Insights:**
After evaluating the performance of several models, Facebook's Prophet has the best results containing a small margin of error.

Followed by the Ordinary Least Squares Linear Regression Model, which is not entirely overfit and predicts fairly well.

Most models perform poorly and are overfit, specially those dealing a decision tree nature since, values are placed in buckets and is inefficient for sequential quantitative data.






<a class="anchor" id="WNV"></a>

### [Forecasting the West Nile Virus for the City of Chicago, Illinois & the Chicago Department of Public Health (CPHD)](https://github.com/adam-delreal/Portfolio/tree/master/Forecasting_WNV)

Programmed a supervised model to predict when and where different species of mosquitos will test positive with the West Nile Virus. Permitting the City of Chicago and the Chicago Department of Public Health (CPHD) to efficiently and effectively allocate their resources towards the prevention of the West Nile Virus.

**Tools:**

**Data Acquisition:**

**Exploratory Data Analysis:**

**Machine Learning Models:**

**Insights:**

<a class="anchor" id="Politics"></a>

### [Political Classifier: Classifying Politics Based on News Titles on Reddit](https://github.com/adam-delreal/Portfolio/tree/master/Political_Classifier)

Programmed a political classifier to predict whether a news headline belongs to either a European or American Political subreddit. The purpose was to create a classifier using qualitative data from subreddit headers and news-titles.

**Tools:**

**Data Acquisition:**

**Exploratory Data Analysis:**

**Machine Learning Models:**

**Insights:**