# Event Entry Prediction Project

## Introduction

This project aims to predict whether entry to an event will be granted or denied based on various features such as ticket class, gender, age, price of the ticket, bank balance of the ticket buyer, etc. We will explore the dataset, preprocess the data, and then apply different machine learning techniques including Logistic Regression, PCA Analysis, Decision Tree Analysis, and K Means Clustering to develop predictive models and gain insights from the data.

## Dataset Information

- **Order:** Order of buying the tickets
- **Entry:** 0 indicates denial, 1 indicates approval
- **Ticket class:** Different types of tickets (e.g., 1, 2, 3)
- **Sex:** Gender of the ticket buyer
- **Age:** Age of the ticket buyer
- **Price:** Price of the ticket
- **Name:** Name of the ticket buyer
- **Ticket:** Ticket number
- **Bank Balance:** Bank balance of the ticket buyer

## Steps performed during analysis

1. **Data Exploration and Visualization :**
   - Explored the "Event_entry" dataset.
   - Provided visualizations such as histograms, scatter plots, or box plots to understand the distribution of different features.

2. **PCA Analysis :**
   - Split the dataset into training and testing sets and encoded the variables where needed.
   - Developed a Logistic regression model to predict if the entry to the event will be granted or denied.
   - Used PCA to reduce dimensions (tried with 2, 4, and 6 dimensions) and evaluated its impact on the model's performance.
   - Compared the out-of-sample performance with that of a LASSO Logistic Regression Model.

3. **Decision Tree Analysis :**
   - Split the dataset into training and testing sets and encoded the variables when needed.
   - Preprocessed the data as necessary.
   - Trained the decision tree classifier using the training data.
   - Predicted the accuracy of the model using the test data and explained the results.

4. **K Means Clustering :**
   - Used the Entry_event database and used the Age and Price columns only.
   - Performed K means clustering for different values of K.
   - Determined the appropriate value of K and explained the reason for picking it.
   - Created the clusters using the chosen value of K.
   - Ploted a graph to show the different clusters.

## Conclusion

This project aimed to explore various machine learning techniques for predictive modeling and clustering analysis on the given dataset. By implementing these techniques, I seeked to develop models that can accurately predict event entry approval and gained insights into the underlying patterns in the data.
