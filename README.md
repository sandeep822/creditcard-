# creditcard-

Information on credit card transactions is included in the dataset that has been supplied. There are 31 columns linked to each transaction, and each row represents a transaction. Creating a machine learning model that can accurately identify fraudulent credit card transactions is the main goal of this project. Financial organizations are very concerned about fraudulent transactions because they have the potential to cause large losses in money. To reduce these losses and safeguard clients, the objective is to develop a model that can precisely recognize these kinds of transactions.

There are 31 columns and 21,878 rows in the dataset. The columns list numerous attributes related to each transaction, and each row represents a credit card transaction. The three most important columns in the dataset are "Class," a binary variable with values of 0 or 1, "Time," which shows the amount of time that has passed between transactions, and "Amount," which shows the amount of each transaction. A transaction is considered fraudulent if the Class value is 1, and non-fraudulent if it is classed as 0.

The collection includes numerical features with the V1, V2, V3, and V28 prefixes. These characteristics most likely come from dimensionality reduction for security and privacy purposes. Other transaction attributes are represented by extra columns such as V22, V23, V24, and so forth.

#Combining classifiers via majority vote

![image](https://github.com/sandeep822/creditcard-/assets/50867031/3f848b62-af63-47e5-a597-6b6688066882)

The above code is essential for evaluating and comparing the performance of an ensemble classifier and four individual classifiers using ROC curve analysis. The ROC curve visually showcases the trade-off between true positive and false positive rates, making it easier to gauge the classifiers' discriminatory power across various thresholds. By calculating the area under the ROC curve (AUC), this code quantifies and compares the overall performance of each classifier. The resulting AUC values are displayed in a legend for straightforward performance assessment. The analysis is a crucial step in assessing and fine-tuning classifiers, aiding in the selection of the most suitable model for a given task. The blue dashed line represents a KNN classifier, serving as a benchmark with an AUC of 0.90, and classifiers strive to achieve ROC curves above this line, indicating superior performance compared to random guessing. Overall, this code provides a comprehensive method for evaluating and optimizing machine learning models.

![image](https://github.com/sandeep822/creditcard-/assets/50867031/b5751f15-ac5c-4268-a899-d0de0168478a)

#Using Bagging and AdaBoost

![image](https://github.com/sandeep822/creditcard-/assets/50867031/341af306-0a48-4278-a838-462811881303)

four different classifiers are evaluated and compared using Receiver Operating Characteristic (ROC) curve analysis. Each classifier, including Decision Tree, Majority Voting (an ensemble technique), Bagging, and AdaBoost, is assessed for its ability to distinguish between positive and negative instances.

The ROC curves for each classifier are plotted with different line styles and colors, making it easy to visually compare their performance. The area under the ROC curve (AUC) is calculated for each classifier, providing a quantitative measure of their overall discriminative power.

The legend displays the AUC values for each classifier, facilitating a clear performance assessment. The gray and orange dashed line represents a Decision tree and Bagging classifier, serving as a reference point with an AUC of 0.87. Classifiers aim to achieve ROC curves above this line, indicating their effectiveness in making predictions.

This analysis is crucial for selecting the most suitable classifier for a specific task and helps in understanding the trade-offs between true positive and false positive rates.

![image](https://github.com/sandeep822/creditcard-/assets/50867031/c6fbb950-8370-4434-ad12-79c1db5cfe39)

K_Means Clustering

![image](https://github.com/sandeep822/creditcard-/assets/50867031/1b27df4e-5692-4653-be5c-32c84ad79fb2)

A mix of cluster labels and potential numerical values. It suggests that there are three clusters (Cluster 1, Cluster 2, Cluster 3) with corresponding labels and centroids.

![image](https://github.com/sandeep822/creditcard-/assets/50867031/6189bae2-be06-4361-82b7-71ccf2eafac7)

K-Means clustering with two clusters to the dataset and visualizes the resulting clusters and centroids. Data points in cluster 1 are plotted in light green squares, and those in cluster 2 are shown in orange circles. The cluster centroids are marked with red asterisks. The legend labels the clusters and centroids. The plot includes a grid for reference, and it's presented with a tight layout.

![image](https://github.com/sandeep822/creditcard-/assets/50867031/02173ed9-660d-4516-ab86-27d5669d0495)



