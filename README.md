# Prodigy InfoTech Internship - Task 3

## Build a Decision Tree Classifier for Customer Purchase Prediction

### Overview
In this project, I completed Task 3 of my internship at Prodigy Infotech, which involved building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used for this task is the Bank Marketing dataset from the UCI Machine Learning Repository.

### Dataset
- **Dataset Name:** Bank Marketing Dataset
- **Source:** https://archive.ics.uci.edu/dataset/222/bank+marketing
- **Description:** This dataset contains information about customers, including their age, job, marital status, education, balance, contact method, and whether they made a deposit or not.

### Data Preprocessing and Analysis
- Loaded the dataset into a pandas DataFrame.
- Renamed the target variable column to 'deposit'.
- Explored the dataset's shape, columns, and data types.
- Checked for missing values, duplicates, and outliers.
- Visualized the distribution of categorical variables using count plots.
- Plotted box plots to identify outliers in numerical variables.
- Handled outliers using the Interquartile Range (IQR) method.
- Checked for multicollinearity among numerical variables using a correlation matrix.
- Encoded categorical variables using Label Encoding.

### Model Building and Evaluation
- Split the dataset into training and testing sets.
- Built a Decision Tree Classifier with Gini criterion and evaluated its performance.
- Built another Decision Tree Classifier with Entropy criterion and evaluated its performance.
- Evaluated model performance using accuracy score, confusion matrix, and classification report.
- Visualized the decision tree using plot_tree() function from scikit-learn.

### Results
- Both Decision Tree models achieved decent accuracy on the test set.
- The Gini-based model achieved an accuracy of 88.83%.
- The Entropy-based model achieved an accuracy of 88.85%.
- The decision tree visualizations provide insights into the model's decision-making process.

### Conclusion
Overall, this project helped me gain hands-on experience in building and evaluating decision tree classifiers for predictive modeling tasks. I look forward to applying these skills to real-world problems in my future endeavors.

