
# Predicting Loan Default Risk Using Machine Learning

This project demonstrates how machine learning models can be applied to predict whether a loan applicant will default. The dataset used is the **UCI Statlog German Credit Data**, which contains socio-economic and financial information on 1,000 borrowers, labeled as either **Good (1)** or **Bad (2)** credit risk. The objective of this project is to explore, preprocess, and build predictive models to determine the credit risk of borrowers.

## **Research Questions**
1. How can we predict the default risk of a borrower based on socio-economic and financial features using machine learning models?
2. Which machine learning algorithms (Logistic Regression, Random Forest, XGBoost) work best for classifying the default risk of borrowers?
3. What are the most important features that determine loan default risk?

## **Dataset Details**
- **Name:** German Credit Data
- **Source:** UCI Statlog (German Credit Data) Dataset
- **Contributors:** This dataset was compiled by Prof. Hans Hofmann (University of Hamburg).
- **Details:** The dataset contains socio-economic and financial information of 1,000 borrowers. Each instance is labeled as **Good (1)** or **Bad (2)** credit risk.

## **Libraries Used**
- **pandas** for data manipulation and analysis.
- **matplotlib** and **seaborn** for data visualization.
- **scikit-learn** for machine learning models and evaluation metrics.
- **xgboost** for gradient boosting models.
- **time** for performance monitoring.

## **Steps Performed in the Notebook**
1. **Import Libraries:** All necessary libraries for data manipulation, machine learning, and evaluation are imported.
2. **Data Loading and Preprocessing:**
   - The **German Credit Dataset** is loaded and inspected.
   - Categorical variables are encoded numerically, and missing values are handled.
   - Features such as **credit amount**, **employment duration**, and **purpose** are used to train the models.
3. **Model Training:**
   - **Logistic Regression**, **Random Forest**, and **XGBoost** models are trained to predict the credit risk.
4. **Model Evaluation:**
   - The models' performances are evaluated using accuracy, precision, recall, F1-score, and ROC-AUC.
   - **Confusion Matrix** and **Classification Report** are generated for model comparison.
5. **Hyperparameter Tuning:** GridSearchCV is used to fine-tune the hyperparameters for Random Forest and XGBoost.
6. **Final Model Selection:** Based on performance metrics, the best performing model is selected.

## **How to Run the Notebook**
1. Clone the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn xgboost
   ```
3. Download the **German Credit Dataset** or use your own dataset structured similarly.
4. Open the notebook in **Jupyter Notebook** or **Google Colab**.
5. Execute all the cells to perform data preprocessing, model training, and evaluation.

## **Results**
This project compares multiple machine learning models for predicting loan default risk. The **Random Forest** and **XGBoost** models provide strong performance in terms of accuracy, precision, recall, and ROC-AUC. **Feature importance** is analyzed to identify the key factors influencing the default risk prediction.

## **Contributions**
Feel free to contribute by:
- Adding new machine learning algorithms for loan default risk prediction.
- Enhancing data preprocessing techniques.
- Improving model interpretability.

## **License**
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
