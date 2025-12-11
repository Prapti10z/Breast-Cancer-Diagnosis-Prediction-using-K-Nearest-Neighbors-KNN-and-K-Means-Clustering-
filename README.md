Breast Cancer Classification (KNN & K-Means):

This project uses machine learning to classify breast cancer tumors as Malignant (M) or Benign (B).
We used two algorithms: K-Means Clustering and K-Nearest Neighbors (KNN).

Project Steps

1. Data Cleaning
Removed id and Unnamed: 32 columns
Converted diagnosis:

M → 1
B → 0

2. Feature Scaling

Applied Min-Max Normalization so all features are between 0 and 1.

3. Train-Test Split
80% training
20% testing
Algorithms Used

K-Means (k = 2)

* Used to group the data into 2 clusters
* Compared clusters with actual diagnosis
* Shows how data naturally separates

KNN Classifier (k = 5)

* Trained on the dataset
* Tested on 20% data
* Calculated:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * 
Optimal k

* Checked k = 1 to 20
* Found the best k-value with highest accuracy
  
Visualizations

* K-Means cluster plot
* Actual diagnosis plot
* Confusion matrix
* Accuracy vs K graph
Results
* KNN gives high accuracy for predicting cancer type
* K-Means gives a good idea of natural grouping
* Normalization improves both algorithms
  
📁 Includes
* Google Colab notebook
* All code for preprocessing, training, and evaluation
* This simple description.


