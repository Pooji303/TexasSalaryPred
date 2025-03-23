# *Texas Salary Prediction*

## *Project Overview*
The *Texas Salary Prediction* project aims to analyze salary trends and build predictive models to estimate salaries based on various factors. The dataset includes demographic, educational, and occupational attributes to provide insights into salary distribution across different job roles in Texas. This project will help understand salary determinants, aiding businesses and individuals in making informed salary-related decisions.

## *Problem Statement*

### *Task 1: Data Analysis & Insights*
- Perform an in-depth *Exploratory Data Analysis (EDA)* to understand salary distribution.
- Identify trends, correlations, and key salary-influencing factors.
- Use *statistical and visualization techniques* to uncover insights.

### *Task 2: Salary Prediction Model*
- Develop a *Machine Learning model* to predict salaries based on multiple features.
- Compare various models such as *Linear Regression, Decision Trees, and Random Forest* to find the best-performing one.
- Optimize the model using *feature selection, hyperparameter tuning, and cross-validation*.

### *Task 3: Model Performance & Comparison*
- Compare different models using evaluation metrics like *Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score*.
- Analyze feature importance and model explainability for better decision-making.
- Recommend the most accurate and efficient model for real-world deployment.

### *Task 4: Challenges & Solutions*
- *Data Cleaning & Preprocessing:* Handling missing values, outliers, and categorical encoding.
- *Feature Engineering:* Selecting relevant features and performing transformations.
- *Model Selection & Optimization:* Balancing accuracy and interpretability for practical use.

## Dataset Information
The dataset consists of various attributes influencing salary levels, including:

| *Feature Name*   | *Description* |
|--------------------|----------------|
| *Occupation*     | Job role or position. |
| *Education Level* | Level of education required. |
| *Experience*     | Years of experience in the field. |
| *Industry*       | Employment sector. |
| *Location*       | Job location within Texas. |
| *Salary*         | Annual salary of the employee (Target Variable). |

*Dataset Link:* [Download Dataset](#)

## *Repository Structure*

├── data/ # Raw and processed datasets
│   ├── raw/ # Original dataset
│   ├── processed/ # Cleaned and feature-engineered dataset
│
├── notebooks/ # Jupyter notebooks for EDA, modeling, and analysis
│   ├── 01_EDA.ipynb # Exploratory Data Analysis
│   ├── 02_Feature_Engineering.ipynb # Feature Selection & Engineering
│   ├── 03_Model_Training.ipynb # Model Training & Evaluation
│   ├── 04_Model_Comparison.ipynb # Model Comparison & Insights
│
├── src/ # Python scripts for data processing and modeling
│   ├── data_processing.py # Data cleaning and transformation scripts
│   ├── model_training.py # Model training and evaluation scripts
│   ├── utils.py # Helper functions
│
├── reports/ # Reports & insights
│   ├── analysis.pdf # Detailed project analysis
│   ├── summary.md # Summary of findings


## *Technologies Used*
- *Programming Language:* Python  
- *Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- *Machine Learning Models:* Linear Regression, Decision Trees, Random Forest, XGBoost  

## *Results & Key Findings*
- The model successfully predicts salaries with an *R² score of 95%*.
- *XGBoost (After Tuning) appears to be the best model overall for the dataset.*  
  - *R² = 0.955972*  
  - *MAE = 0.03914*  
  - *MSE = 0.00736*  
  - It performs consistently well across all key metrics.
- *Experience and Education Level* are the most significant predictors of salary.

