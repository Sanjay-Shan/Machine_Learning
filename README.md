# Ebay's Machine Learning Competition

E-Commerce is replacing the mainstream shopping experience and the experience of shopping on an E-Commerce website is influenced by a lot of factors. One of the key factors is suggesting products and services to customers based on their likings. A lot of studies have been made and improvements have been made focusing on this problem. And most of the solutions to this problem are based on machine learning techniques and there are a lot of ranking algorithms.  

The accuracy of shipping estimates is another crucial factor, and it plays a significant role in providing a hassle-free and trusty customer experience. However, this area has not received enough attention within the machine learning community despite its growing importance in the new online world. In this project, we are going to dive into this problem and propose viable solutions with proper justifications. 

# Methodology

Initially a thorough preprocessing and feature engineering is done and finally 8 sets of machine learning models are trained so as to check which of them performs the best on the underlying data.

Following machine learning models have been tried in this project namely:
1) linear regression 
2) Random_forest
3) Linear Regression + PCA
4) Adaboost
5) XGboost
6) Histogram gradient boost
7) gradient boost
8) Cat boost
9) Voting Regressor (It is basically a combination of all the machine learning models trained above)

Here each and every model predicts the duration of delivery ,and once the duration is obtained from the model , a post processing is performed to get the actual predicted delivery date of the item.

# Conclusion

In our case , we are getting Linear Regression and Adaboost with Linear Regression as the best model for the delivery date prediction system.

Two metrics have been defined here to measure the accuarcy of the model
Top 1 accuracy - 70.53% (exactly matching the actual delivery date with the predicted delivery date)
Top 2 accuracy - 99.97% (If there exits a day difference between actual delivery date and the predicted delivery date, then it is considered as TP in the calculation of the accuracy)


