---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

### Projects with Python

[Time series with google stock](https://github.com/diwu437/diwu-github.io/blob/master/TimeSeries_with_Google_Stock.ipynb)

In this project, my goal is to predict future google stock closing price based on past time series data. 
In order to transform the data into a stationary process which makes the it predictable, I have implemented methods such as de-trending and de-seasoning. 
Next, I have built three time-series model including AR, MA and ARIMA and selected ARIMA as the final predication model based on best residual fitting performance. 
Finally, I did hyperparameter tuning for ARIMA model via grid-search to find the optimize p and q. Adding back the predication value as well as trend and seasoning back to the original data to get the final predication. 

[![](/images/error fitting.png)](https://github.com/diwu437/diwu-github.io/blob/master/TimeSeries_with_Google_Stock.ipynb)

--- 


[Bank customer churn prediction](https://github.com/diwu437/diwu-github.io/blob/master/Bank_customer_churn_prediction.ipynb)

In this project, I use supervised learning models to identify customers who are likely to churn in the future. Furthermore, I will analyze top factors that influence user retention. 
I have transformed gender and geography varibles to binary varibles to enhance model performance. And then i have standardized features for the same purpose.
Based on the Accuracy socre, i picked Logistic regression as my final model with its best hyperparameters.
Identified Age as the primary facotr that effect churn rate based on feature importance.

[![](/images/1.png)](https://github.com/diwu437/diwu-github.io/blob/master/Bank_customer_churn_prediction.ipynb)

---

[Document clustering and topic modeling](https://github.com/diwu437/diwu-github.io/blob/master/Document_Clustering_and_Topic_Modeling_ipynb%E2%80%9D.ipynb)

In this project, I used unsupervised learning models to cluster unlabeled documents into different groups and identify their latent topics/structures.
The data consist over 900k customer reviews from a watch retailer. 
For the first goal, I grouped customer reviews with k-means by their TF-IDF. Then I will select 6 most important words with highest importance. The “importance” here refer to highest TF-IDF which come from the center of each cluster. 
For the second goal, I used Latent Dirichlet Allocation model to find latent topics and assign them to each document. Lastly, I selected top 14 key words for each topics.  

[![](/images/LDA.png)](https://github.com/diwu437/diwu-github.io/blob/master/Bank_customer_churn_prediction.ipynb)

---

[Predicting negative comments from tweets](https://diwu437.github.io/files/text classification.pdf)


The goal of final project is using the 'complaint1700' and 'non-complaint1700' file to train a robust classification model, which can be used afterwards to test if a new tweet is negative and help the company to separate the non-negative tweets. 
I start by removing punctuation characters and stop words. And the trained three models and selected Native Bayes model which yields the highest predicting accuracy.  
Lastly, I applied the model on the test dataset and resulting in accuracy around 77%.


[![](/images/text.png)](https://diwu437.github.io/files/text classification.pdf)


---

[Amazon prime movie view time](https://github.com/diwu437/diwu-github.io/blob/master/%E2%80%9CAmazon_prime_Movie_View_Time_Predication_ipynb%E2%80%9D.ipynb)

In this project, I leveraged on machine learning model to make predication on view time of Amazon prime movie.
I have performed exploratory data analysis and preprocessed raw sales and product data by handling missing values, encoding categorical features and scaling features. 
Selected best model based on predication accuracy and identified the key factors that affect view time performance.  

[![](/images/amazon1.png)](https://github.com/diwu437/diwu-github.io/blob/master/%E2%80%9CAmazon_prime_Movie_View_Time_Predication_ipynb%E2%80%9D.ipynb)

--- 

### Projects with Spark

[SF Crime analysis with Spark](https://diwu437.github.io/files/SF_Crime analysis with Spark.html)

The goal of this project is to analysis the crime rate of San Francisco and gain insights on policy and travel suggestion. I have built data processing pipeline based on Spark SQL for big data online analytical processing. Explored and visualized the variation of spatial distribution of incidents over time. 

[![](/images/SF CRIME.png)](https://diwu437.github.io/files/SF_Crime analysis with Spark.html)

---

### Projects with R

[Lanuching a new product with kiwi](https://diwu437.github.io/files/Lanuching a new product with kiwi.pdf)

In this project, we are supposed to do the profit maximization with multi-segment and multi-product for the sake of analyzing the best pricing strategy for the new product “Kiwi Bubbles”. Under the assumption that the unit costs are all $0.5 and market size is 1000 consumers, the data set we had records the choices of soft drink of 359 consumers over the course of 3 years. More details about how we manipulated the logit model are as follows.

[![](/images/profit with segmentation.png)](https://diwu437.github.io/files/Lanuching a new product with kiwi.pdf)
