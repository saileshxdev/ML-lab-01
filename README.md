# ML-lab-01
Lab 01: Build and Test Your First ML Classifier (KNN on Iris)
🎯 Objective

Load and explore the Iris dataset.

Visualize feature relationships using Seaborn pairplots.

Train and evaluate a K-Nearest Neighbors (KNN) classifier.

Understand distance-based learning in vector space.

Interpret classification results with accuracy, confusion matrix, and class probabilities.

📝 Steps

Setup

Imported libraries: numpy, pandas, matplotlib, seaborn, sklearn.

Loaded Iris dataset into a Pandas DataFrame.

Data Exploration

Checked dataset shape, statistics, and missing values.

Plotted class distribution.

Used Seaborn pairplot to visualize feature relationships.

Model Building

Train-test split (80/20).

Trained KNN classifier with k = [1, 3, 5, 7].

Compared accuracy for different values of k.

Plotted accuracy vs k and generated confusion matrix.

Wrap-up

Summarized performance.

Added observations and plots to notebook.

Pushed to GitHub with README.

📊 Results & Observations

Accuracy:

Best accuracy achieved for k=3 or k=5 (~97%).

k=1 overfits (memorizes training points).

k=7 slightly underfits.

Pairplot Insights:

Setosa is clearly separable from others.

Versicolor and Virginica overlap in petal features → harder to separate.

Confusion Matrix:

Setosa always classified correctly.

Most errors occur between Versicolor and Virginica.

Conclusion:
KNN works well for Iris; the choice of k balances bias vs variance.

📂 Files in this Repo

Lab01_KNN_Iris.ipynb – Jupyter/Colab notebook

pairplot.png – feature visualization

accuracy_vs_k.png – accuracy vs k plot

confusion_matrix.png – confusion matrix
