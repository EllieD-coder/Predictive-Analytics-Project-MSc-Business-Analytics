# Predictive Analytics Individual Coursework

## Description
This project involves comprehensive data analysis and predictive modeling on a dataset of cosmetic products. The primary objectives include data exploration, preprocessing, exploratory data analysis (EDA), model building, and fine-tuning using various machine learning algorithms.

## Project Structure

1. **Preliminary Data Exploration**
   - **Data Import and Initial Exploration:** Load and inspect the dataset to understand its structure and basic statistics.
   - **Data Structure Observation:** Check data types, missing values, and statistical summaries.

2. **Exploratory Data Analysis (EDA)**
   - **Data Cleaning:** Remove non-ingredient entries and standardize the ingredient lists.
   - **Distribution Analysis:** Explore distributions of numerical attributes such as price and rank.

3. **Predictive Modeling**
   - **Model Selection:** Implement various models, including Random Forest and Neural Networks, to predict the target variable.
   - **Cross-Validation:** Perform cross-validation to ensure model robustness.
   - **Hyperparameter Tuning:** Fine-tune model parameters using GridSearchCV and RandomizedSearchCV.

4. **Model Evaluation**
   - **Performance Metrics:** Evaluate models using metrics such as MSE, MAE, and R-squared.
   - **Feature Importance:** Visualize feature importance for the Random Forest model.
   - **Comparison of Models:** Compare the performance of different models and select the best-performing one.

5. **Final Model and Solution**
   - **Save and Load Models:** Save the final models and performance metrics using Joblib.
   - **Final Evaluation:** Compare actual vs. predicted values for the fine-tuned models.

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, keras)
- Jupyter Notebook

## Instructions to Run the Project
1. **Install Dependencies:** Ensure all required libraries are installed.
2. **Load the Dataset:** The dataset should be placed in the same directory as the notebook or specify the correct path.
3. **Execute the Notebook:** Run the notebook cells sequentially to reproduce the analysis and results.

## Repository Structure
- `MSIN0097 Predictive Individual Coursework.ipynb`: Main Jupyter Notebook containing the entire analysis and model building process.
- `cosmetics.csv`: Dataset file used for the analysis.
- `README.md`: Project description and instructions.

## Author
Elena docheva
