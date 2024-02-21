# Machine Learning Project: Fault Detection in Tennessee Eastman Process Simulation Dataset

## Introduction
In this project, we aimed to develop a machine learning model for fault detection using the Tennessee Eastman Process Simulation dataset. The dataset contains data referenced in Rieth et al. (2017) and includes fault-free and faulty instances.

### Steps Taken 🚀
1. **Data Loading**: Downloaded the dataset from [Kaggle](https://www.kaggle.com/datasets/averkij/tennessee-eastman-process-simulation-dataset).
2. **Data Preprocessing**: Cleaned and preprocessed the data to handle missing values and normalize features.
3. **Feature Engineering**: Extracted relevant features and engineered new features if necessary.
4. **Model Selection**: Explored various machine learning algorithms such as Random Forest, Support Vector Machines, and XGBoost.
5. **Model Training**: Trained the selected models on the fault-free training data.
6. **Model Evaluation**: Evaluated model performance using fault-free testing and faulty testing data.

## Results
After extensive experimentation and evaluation, It is concluded that XGBoost outperformed other algorithms with a cumulative accuracy of 89.7% in detecting all faults.

## Conclusion
This project demonstrates the effectiveness of machine learning in fault detection using the Tennessee Eastman Process Simulation dataset. XGBoost emerged as the top-performing model, showcasing its potential in industrial anomaly detection tasks.

