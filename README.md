

* This Flask Project is a data Science project in which I have used Algerian Forest Fire Data Set from https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset project *

## 2. DATA COLLECTION AND UNDERSTANDING

* I used a dataset on **Algerian Forest Fires** from UCI. The dataset contains a culmination of forest fire observations and data in two regions of Algeria: the Bejaia region and the Sidi Bel-Abbes region. The timeline of this dataset is from **June 2012 to September 2012**. In this project, we focused on whether certain weather features could predict forest fires in these regions using few Classification algorithms.


* As per the Task given i choose regression problem to predict fire weather index

## 3. DATA EXPLORATION

* In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Forest fire by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn. It is always a good practice to understand the data first and try to gather as many insights from it.


Below are tasks to be performed in EDA:

**1. Importing Libraries**


**2. Data Cleaning for EDA Report**

**3. Exploratory Data Analysis (EDA) on all Features**


## Next I have made use of following steps:

a. Feature Engineering
b. Label Encoding, For class feature,
c. Data Visualization
d. Creating Heat map using Correlation
e. EDA( Exploratory Data Analysis )
f. Splitting  the Data Into Train Test Split

I used 3 Regression Models,

1. Linear Regression 
2. Ridge Regression
3. Lasso Regression
4. Ridge CV 
5. Lasso CV

In these Regressions I got to know Ridge Regression is performing well and I have included this in my Pickle File.
I have used Pickle Files to load and I have created a Flask application for  predicting the Algerian Fire "FWI" Feature.
"""

