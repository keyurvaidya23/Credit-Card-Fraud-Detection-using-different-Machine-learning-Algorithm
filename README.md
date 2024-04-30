# Credit-Card-Fraud-Detection-using-different-Machine-learning-Algorithm
This project aims to detect fraudulent transactions using credit card data. The Python script utilizes several machine learning models including Logistic Regression, Random Forest, and Decision Tree classifiers. The models are evaluated based on accuracy, precision, recall, and F1-score to determine their effectiveness in fraud detection.

Project Structure
creditcard.csv - The dataset file used for analysis.
fraud_detection.py - Python script for preprocessing data, training models, and evaluating their performance.
requirements.txt - List of Python packages required to run the project.
Setup and Installation
Prerequisites
Python 3.6 or higher
pip or conda for installing packages
Installation
Clone the repository:
git clone https://your-repository-url.git
cd your-project-directory
Install required packages:
pip install -r requirements.txt
Or if you are using conda, you might prefer:
conda create --name fraud-detection --file requirements.txt
conda activate fraud-detection
Running the Script
Execute the script:
Navigate to the project directory and run:
python fraud_detection.py
View Results:
The script will output classification reports, confusion matrices, and accuracy scores for each model.
A bar chart comparing the performance of the models will also be displayed.
Features and Models
Data Preprocessing: Scaling of numerical features, handling of missing values, and removal of duplicates.
Predictive Models:
Logistic Regression: Baseline model for comparison.
Random Forest: Ensemble model for improved accuracy.
Decision Tree: A simple model for baseline comparison.
Evaluation Metrics: Accuracy, Precision, Recall, F1 Score.
Contributing
Contributions to this project are welcome. Please ensure any pull requests are validated locally for performance and correctness.
