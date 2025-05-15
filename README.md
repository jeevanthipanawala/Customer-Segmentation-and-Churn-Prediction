 Customer Segmentation and Churn Prediction 
(An Assignment of Machine Learning Course in Masters Programme in Software Engineering) - Blekinge Institutie of Technology
====================================================================================================================================================

Overview
--------
This project focuses on analyzing customer behavior through machine learning techniques, with the aim of segmenting customers, predicting churn, and providing marketing recommendations. The key components of the project include:

1.Customer Clustering (code:customer_segmentation.ipynb):

Utilized the k-means clustering algorithm to group customers based on their purchasing behavior.

Employed Silhouette analysis to determine the optimal number of clusters and validate the clustering results.

2.Churn Prediction Model (code:churn_prediction.ipynb):

Built a churn prediction model using the Gradient Boosting algorithm.

Improved model performance through hyperparameter tuning.

Assessed the model's performance using metrics such as confusion matrix, precision, recall, F1-score, and AUC-ROC values.

3.Marketing Recommendations (code:marketing_recommendations.ipynb):

Analyzed purchase patterns of high-risk customers based on predicted churn probabilities.

Provided insightful recommendations for planning marketing campaigns to retain these customers.

Prerequisites
-------------
1. **Python**: Ensure Python 3.7+ is installed.
2. **Required Libraries**:
   - All the required libraries are given in the imports section of .ipynb files.
   - Install the mentioned libraries using `pip install <libraryname>`
3. **Dataset**: The analysis uses  the data in `online_retail_II.xlsx` file. Place this file in 'Data' directory.
4. Inside the code, intermediate data files are saved into the same 'Data' directory and they are used in the code.


project-directory/
├── Data/
│   └── online_retail_II.xlsx (Download from here https://archive.ics.uci.edu/dataset/502/online+retail+ii)
├── src/
│   └── customer_segmentation.ipynb
│   └── churn_prediction.ipynb 
    └── marketing_recommendations.ipynb
└── readme.txt

Setup Instructions
------------------
1. Download the repository containing the notebook and the dataset.
2. Navigate to the project directory
3. Install the required libraries mentioned in the imports section of each notebook before running each file
4. Ensure the dataset ('online_retail_II.xlsx') is available in the Data folder.

Running the Code
----------------
1. Open the Jupyter Notebooks ( order: 1.customer_segmentation.ipynb 2.churn_prediction.ipynb 3.marketing_recommendations.ipynb
2. Execute each cell in sequential order:


Output
------
1. Customer Segments and Silhoette Analysis Graphs
2. Churn Prediction model performance metrics analysis
3. Visualizations for marketing recommendations

Notes
-----
- Ensure your Python environment has all necessary permissions to read and write files.

Authors
-------
- Jeevanthi Panawala
- Sree Dharani Machunuru


# Customer-Segmentation-and-Churn-Prediction
Customer Segmentation, Churn Prediction and Marketing Recommendations
