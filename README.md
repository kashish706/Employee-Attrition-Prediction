# Employee Attrition Prediction Using MongoDB and Machine Learning

## Project Overview
This project focuses on analyzing and predicting employee attrition using MongoDB, PyMongo, Python, and Machine Learning.

Employee attrition refers to employees leaving an organization. The project uses employee data to identify patterns associated with attrition and build machine learning models to predict whether an employee is likely to leave.

## Objectives
- Store and manage employee data using MongoDB.
- Perform database operations using PyMongo.
- Clean and preprocess the dataset.
- Analyze employee attrition patterns.
- Build and evaluate machine learning models.
- Compare model performance using evaluation metrics.

## Dataset
- **Dataset:** IBM HR Analytics Employee Attrition Dataset
- **Source:** [Kaggle – IBM HR Analytics Employee Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Total Records:** 1,470
- **Original Features:** 36
- **Employees Who Stayed:** 1,233
- **Employees Who Left:** 237

## Technologies Used
- Python
- MongoDB
- PyMongo
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Dataset collection and loading.
2. MongoDB database creation.
3. Employee records insertion using PyMongo.
4. Data retrieval and aggregation.
5. Data cleaning and preprocessing.
6. Feature encoding and train-test splitting.
7. Machine learning model development.
8. Model evaluation and comparison.

## Machine Learning Models
The following models were implemented:

1. Logistic Regression
2. Logistic Regression with Balanced Class Weights
3. Decision Tree Classifier

## Model Evaluation Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 87.07% | 0.7059 | 0.3380 | 0.4571 |
| Balanced Logistic Regression | 78.00% | 0.3917 | 0.6620 | 0.4921 |
| Decision Tree | 73.02% | 0.3125 | 0.5634 | 0.4020 |

## Key Findings
- The original Logistic Regression model achieved the highest accuracy of 87.07%.
- Balanced Logistic Regression achieved the highest recall and F1-score.
- Class balancing improved the model's ability to identify employees who left.
- The project demonstrates how MongoDB and machine learning can work together for employee data analysis.

## Repository Contents
- `Employee_Attrition_Prediction.ipynb` – Jupyter Notebook containing database operations, preprocessing, model training, and evaluation.
- `README.md` – Project documentation.
- `Project_Report.pdf` – Detailed project report.
- `Project_Presentation.pptx` – Project presentation.

## How to Run
1. Clone or download this repository.
2. Install Python and MongoDB.
3. Install the required Python libraries used in the notebook.
4. Download the dataset from the Kaggle source linked above.
5. Place the CSV file in the appropriate project data folder.
6. Open the Jupyter Notebook.
7. Ensure MongoDB Server is running.
8. Execute the notebook cells in order.

## Conclusion
This project successfully demonstrates employee attrition analysis and prediction using MongoDB, PyMongo, and machine learning. It compares multiple classification models and highlights the importance of recall and F1-score when identifying employees who may leave an organization.

**Note:** Model predictions are indicators based on available data and should not be treated as definitive decisions about employees.
