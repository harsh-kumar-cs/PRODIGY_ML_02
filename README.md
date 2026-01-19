# PRODIGY_ML_02
# Customer Segmentation using K-Means Clustering

## Overview
This project demonstrates **customer segmentation** using **K-Means clustering**, an unsupervised machine learning algorithm.  
The objective is to group retail customers based on their purchasing behavior to help businesses better understand and target different customer segments.

---

## Dataset
The dataset contains the following attributes:
* Customer ID  
* Gender  
* Age  
* Annual Income (k$)  
* Spending Score (1–100)

For clustering, only **Annual Income** and **Spending Score** were used, as they directly represent customer purchasing capacity and behavior.

---

## Methodology
The project follows these steps:
* Load and explore the dataset  
* Remove irrelevant features  
* Select numerical attributes for clustering  
* Use the **Elbow Method** to determine the optimal number of clusters  
* Apply **K-Means clustering**  
* Visualize the resulting clusters using a scatter plot  

---

## Visualization
* Each point in the scatter plot represents a customer  
* Different colors indicate different clusters  
* Cluster centers show the average behavior of customers within each group  

This visualization helps clearly identify distinct customer segments.

---

## Insights
The clustering reveals meaningful customer groups such as:
* High-income, high-spending customers  
* High-income, low-spending customers  
* Low-income, high-spending customers  
* Low-income, low-spending customers  
* Average customers  

These insights can be used to design targeted marketing and engagement strategies.

---

## Technologies Used
* Python  
* Pandas  
* NumPy  
* Matplotlib  
* Scikit-learn  

---

## Future Improvements
* Add more features such as Age or purchase frequency  
* Apply feature scaling and compare results  
* Experiment with other clustering algorithms  

---

## Conclusion
This project provides a practical introduction to **unsupervised learning** and shows how K-Means clustering can be used to uncover patterns in customer behavior. It serves as a solid foundation for further exploration in machine learning.
