# **Clustering using Ordinal Logistic Regression and OVR Logistic Regression**

## **Project Overview**
This project demonstrates the use of Ordinal Logistic Regression and One-vs-Rest (OvR) Logistic Regression for clustering data points into classes. Ordinal Logistic Regression is particularly suitable for handling target variables with natural ordering, while the OvR model is used as a comparison to highlight its effectiveness. 

## **Dataset**
The dataset used in this project is synthetically generated using the numpy.random.normal function to create distinct clusters of points. Each cluster is centered around a specified mean value and has a defined standard deviation, ensuring separation between clusters. This setup allows for a clear visualization of how different logistic regression models perform in separating and classifying these clusters. The target variable represents the cluster index, which is ordinal in nature, making it suitable for ordinal logistic regression modeling.


## **Usage**
    1. Run notebook/cluster_dataset.ipynb to create and visualize tha dataset.
    2. Follow the workflow by executing the notebooks in the following order:
        a. models/logistic_regressor.ipynb for One vs Rest (OvR) Logistic Regression
        b. models/ordinal_regressor.ipynb for Mord Ordinal Regression

## **Results**

This project provides a comprehensive example of using logistic regression models for clustering, with a focus on ordinal data. It is a valuable resource for understanding how different logistic regression models perform in clustering tasks using synthetic data.

## **License**

This project is open-source and available under the MIT License.