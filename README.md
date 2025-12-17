# CODTECH-Task1

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SK ALTAB HOSSEN

*INTERN ID*:CT04DR1863

*DOMAIN*:MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*:NEELA SANTOSH

##Task 1: Decision Tree Implementation
Project Description

Title: Decision Tree Classifier for Iris Dataset

Introduction The Decision Tree algorithm is one of the most popular and versatile supervised machine learning algorithms used for both classification and regression tasks. It operates by breaking down a dataset into smaller and smaller subsets while simultaneously developing an associated decision tree. The final result is a tree with decision nodes and leaf nodes. A decision node has two or more branches, each representing values for the attribute tested. A leaf node represents a decision on the numerical target. The topmost decision node in a tree which corresponds to the best predictor called the root node. Decision trees can handle both categorical and numerical data.

Algorithm and Approach For this task, I implemented a Decision Tree Classifier using the Scikit-Learn library in Python. The goal was to classify iris flowers into three species (Setosa, Versicolor, and Virginica) based on four physical attributes: sepal length, sepal width, petal length, and petal width.

Data Loading: I utilized the classic Iris dataset provided by Scikit-Learn. This dataset is a standard benchmark in machine learning, consisting of 150 samples with no missing values, making it ideal for demonstrating the algorithm's mechanics.

Data Splitting: To evaluate the model's performance on unseen data, I split the dataset into a training set (80%) and a testing set (20%) using train_test_split.

Model Configuration: I initialized the DecisionTreeClassifier with the criterion='gini'. The Gini Impurity measures the likelihood of an incorrect classification of a new instance of a random variable if that new instance were randomly classified according to the distribution of class labels from the dataset. I also set a max_depth to prevent the tree from overfitting the training data.

Visualization: A crucial part of this task was visualizing the tree structure. Using plot_tree, I generated a graphical representation of the decision logic. This visualization reveals exactly how the model makes decisions—for example, it might first check if the "petal width" is less than 0.8 cm to immediately isolate the Setosa species.

Results and Conclusion The model achieved high accuracy on the test set, demonstrating the effectiveness of Decision Trees for tabular classification tasks. The visualization provided clear insights into feature importance, showing that petal dimensions were more significant discriminators than sepal dimensions for this specific dataset. This project highlights the interpretability of Decision Trees, which is a significant advantage over "black box" models like neural networks.
