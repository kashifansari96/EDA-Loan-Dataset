<h1> 
   Exploratory Data Analysis Project: Loan Defaulter Detection
</h1>

This project demonstrates a comprehensive approach to building a predictive model for loan defaulter detection, encompassing a wide range of data science techniques and methodologies. Key concepts covered in this project include data loading and cleaning, handling missing values, outlier detection and removal, feature engineering, hyperparameter tuning, and model evaluation. The technologies and tools utilized in this project include:

1. Python
2. Pandas and Numpy for data manipulation and cleaning
3.Matplotlib and Seaborn for data visualization
4. Sklearn for preprocessing and model evaluation
5. XGBoost for advanced modeling
6. Jupyter Notebook and Visual Studio Code as IDEs
   
The project workflow begins with loading and cleaning the dataset, addressing missing values, and ensuring data quality. After preprocessing, an Exploratory Data Analysis (EDA) is conducted, which includes visualizing the data using Matplotlib and Seaborn to identify patterns and relationships.

Outlier detection and removal are performed to enhance model accuracy, followed by feature engineering to transform and encode the data. The data is then split into training and testing sets, and a RandomForestClassifier is initially trained to establish a baseline performance.

For hyperparameter tuning, GridSearchCV is employed to optimize the XGBoost model, aiming to improve predictive performance. Model evaluation is conducted using metrics such as the ROC curve, AUC score, and classification report, with a focus on the model's ability to distinguish between defaulters and non-defaulters.
<h2>
   The project concludes with the following key findings:
</h2>


ROC Curve Analysis: The model's ROC curve is well above the diagonal line, indicating it performs significantly better than random guessing.
AUC Score: An AUC of 0.88 suggests that the model has a high ability to distinguish between default and non-default cases.
Feature Importance: The feature importance plot highlights which features are most influential in the model's predictions, with CUSTOMER INCOME being the most critical feature.
This project effectively showcases the practical application of essential data science techniques and emphasizes the importance of thorough model evaluation and selection. The integration of Jupyter Notebook and Visual Studio Code as IDEs facilitated an efficient and streamlined workflow, contributing to the project's success.

