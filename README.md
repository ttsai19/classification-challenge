# Spam Detection with Machine Learning

## Project Overview
This project focuses on developing and evaluating machine learning models to classify email messages as spam or not spam. Two models—Logistic Regression and Random Forest Classifier—are implemented, trained, and compared based on their performance. The objective is to determine which model is better suited for the task of spam detection, providing insights into their effectiveness and applicability in real-world scenarios.

## Dataset
The dataset used in this project is sourced from the [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase). It contains various features representing word and character frequencies in emails, along with a label (`0` for non-spam and `1` for spam). The data is pre-processed to ensure its readiness for training and testing the models.

### Data Source
- [Spam Data CSV](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

## Project Steps
1. **Data Retrieval and Preparation**
   - Loaded the dataset into a Pandas DataFrame and performed an initial exploration.
   - Split the data into training and testing sets.
   - Scaled the feature data using the `StandardScaler` to standardize the input features.

2. **Model Development**
   - Developed a Logistic Regression model and evaluated its performance.
   - Developed a Random Forest Classifier model and evaluated its performance.

3. **Model Evaluation**
   - Compared the accuracy scores of the two models to determine which performed better.

4. **Results**
   - Logistic Regression Accuracy: `92.70%`
   - Random Forest Classifier Accuracy: `95.48%`
