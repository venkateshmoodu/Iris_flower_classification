# Iris_flower_classification
# Project Overview
This project focuses on the classification of Iris flower species using machine learning algorithms. The dataset consists of features such as sepal length, sepal width, petal length, and petal width, which are used to classify the flowers into three distinct species: Iris-setosa, Iris-versicolor, and Iris-virginica.

The goal is to predict the species of an Iris flower based on its features using various machine learning techniques and evaluating their performance.
# Dataset
The dataset used for this project is the Iris flower dataset, which contains 150 samples with four features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
Each sample belongs to one of the three species of Iris flowers.
# Algorithms and Techniques Used
K-Nearest Neighbors (KNN):

KNN is a simple, instance-based learning algorithm that classifies a sample based on the majority class among its nearest neighbors. The value of k was tuned for optimal performance.
Results:
With k=3, accuracy was 96%.
With k=7, accuracy reached 100%.
Performance Metrics:

Confusion Matrix: Used to compute various classification metrics like:
Sensitivity (Recall)
Specificity
Precision
Negative Precision
False Positive Rate (FPR)
False Negative Rate (FNR)
Overall Accuracy
For all species, the model achieved an accuracy of 100%, with perfect scores in sensitivity, specificity, and precision.
# Conclusion
This project successfully demonstrates the application of machine learning to classify Iris flower species based on sepal and petal measurements. Using the K-Nearest Neighbors (KNN) algorithm, the model achieved an outstanding classification accuracy, with a perfect 100% accuracy for certain configurations.

The project also highlights the importance of evaluating model performance through various metrics like sensitivity, specificity, and precision, providing deeper insights into the model's effectiveness.

This implementation serves as an excellent foundation for further exploration and improvements, such as experimenting with different algorithms, tuning hyperparameters, and expanding the dataset. Overall, this project showcases the power of supervised learning techniques for multi-class classification problems and presents a solid introduction to machine learning in practice.
