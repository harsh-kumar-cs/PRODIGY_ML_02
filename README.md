# PRODIGY_ML_02
Customer Segmentation using K-Means Clustering

📌 Overview

This project focuses on customer segmentation using K-Means clustering, an unsupervised machine learning algorithm. The objective is to group customers of a retail store based on their purchasing behavior, helping businesses better understand different types of customers and design targeted marketing strategies.

⸻

📊 Dataset

The dataset contains information about retail customers, including:
	•	Customer ID
	•	Gender
	•	Age
	•	Annual Income (k$)
	•	Spending Score (1–100)

For clustering purposes, Annual Income and Spending Score were selected as they directly reflect a customer’s purchasing capacity and spending behavior.

⸻

🛠️ Methodology

The project follows these steps:
	1.	Data loading and preprocessing
	2.	Feature selection by removing irrelevant attributes
	3.	Determining the optimal number of clusters using the Elbow Method
	4.	Applying K-Means clustering to segment customers
	5.	Visualizing the clusters using a scatter plot
	6.	Interpreting each cluster to extract meaningful insights

⸻

📈 Visualization

The final output includes a 2D scatter plot where:
	•	Each point represents a customer
	•	Colors represent different clusters
	•	Cluster centers indicate average customer behavior within each group

This visualization helps in understanding how customers are distributed across different segments.

⸻

🧠 Insights

The clustering reveals distinct customer groups such as:
	•	High-income high-spending customers
	•	High-income low-spending customers
	•	Low-income high-spending customers
	•	Low-income low-spending customers
	•	Average customers

These insights can be used to tailor marketing and engagement strategies for different customer segments.

⸻

🚀 Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Scikit-learn

⸻

🔮 Future Improvements
	•	Include additional features such as Age or purchase frequency
	•	Apply feature scaling and compare results
	•	Experiment with other clustering algorithms like Hierarchical Clustering or DBSCAN

⸻

✅ Conclusion

This project demonstrates a practical application of unsupervised learning and shows how clustering can be used to uncover patterns in customer behavior. It serves as a solid foundation for understanding customer segmentation techniques in machine learning.
