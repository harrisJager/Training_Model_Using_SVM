README Documentation: Iris Dataset Analysis with Support Vector Machine (SVM)
This README documentation provides an overview of the Python script that uses the Iris dataset to demonstrate data manipulation with Pandas, data visualization with Matplotlib, and machine learning with Support Vector Machine (SVM) using scikit-learn.

Overview
The provided script performs the following tasks:

Data Loading and DataFrame Creation:

Imports necessary libraries, including pandas and sklearn.
Loads the Iris dataset using load_iris from sklearn.datasets.
Creates a Pandas DataFrame (df) from the Iris data.
Data Exploration:

Adds a 'target' column to the DataFrame representing the target labels.
Adds a 'flower_name' column to the DataFrame, which maps the target labels to corresponding flower names.
Displays the first three rows of the DataFrame using print(df[0:3]) to provide a glimpse of the data.
Data Visualization:

Uses matplotlib.pyplot to create a scatter plot of sepal length vs. sepal width for the first 50 samples of the Iris dataset (Setosa species in green and Versicolor species in blue).
Data Splitting:

Splits the dataset into training and testing sets using train_test_split from sklearn.model_selection.
Defines feature variables (X) and target variable (y).
Machine Learning Model:

Imports SVC (Support Vector Classification) from sklearn.svm.
Creates an SVM model (model) and trains it on the training data.
Model Evaluation:

Calculates the accuracy of the model on the test set using the score method.
Prints the accuracy score.
How to Use the Script
Install Dependencies:

Ensure that you have the required libraries installed. You can install them using:

bash
Copy code
pip install pandas scikit-learn matplotlib
Run the Script:

Run the provided Python script in your preferred Python environment.

bash
Copy code
python your_script_name.py
Explore the Results:

Review the printed DataFrame, the scatter plot, and the accuracy score to understand the analysis of the Iris dataset.
Feel free to modify the script to suit your needs or integrate it into your projects. For more information on the libraries used, refer to the official documentation for Pandas, scikit-learn, and Matplotlib.
