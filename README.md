# Bank Dataset: End-to-End Machine Learning Development

This repository contains an end-to-end machine learning project using a bank dataset. The project includes data preprocessing, exploratory data analysis (EDA), and model development, culminating in a trained model saved for deployment.

## Project Overview

This project demonstrates the following steps in an ML pipeline:

1. **Data Loading**: Import and load the dataset.
2. **Data Preprocessing**: Handle missing values, remove duplicates, encode categorical variables, and scale numerical features.
3. **Exploratory Data Analysis (EDA)**:
   - Analyze categorical and numerical columns.
   - Visualize distributions and relationships.
   - Handle outliers using interquartile range (IQR) clipping.
4. **Feature Engineering**: Perform label encoding and feature scaling.
5. **Model Development**:
   - Train multiple models (Logistic Regression, Decision Trees) with and without hyperparameter tuning.
   - Evaluate models using metrics like accuracy.
6. **Model Saving**: Save the trained model using `pickle`.

## Repository Structure

```
.
├── Bank_data_set_ML_model_development_end_to_end.ipynb  # Main Jupyter Notebook
├── bank_preprocess_data.csv                            # Preprocessed dataset
├── bank_data_set.pkl                                   # Saved trained model
├── README.md                                           # Project documentation
```

## Key Features

### Data Preprocessing

- Removed duplicate values.
- Encoded categorical variables using label encoding.
- Scaled numerical variables using `StandardScaler`.

### Exploratory Data Analysis (EDA)

- Visualized distributions of categorical and numerical features using `matplotlib` and `seaborn`.
- Identified and handled outliers.

### Model Development

- Trained models:
  - Logistic Regression
  - Decision Tree Classifier (with and without hyperparameter tuning)
- Performed grid search to optimize hyperparameters for the Decision Tree model.
- Saved the best model for deployment using `pickle`.

### Metrics

Achieved a Decision Tree Classifier accuracy of **[INSERT ACCURACY HERE]** after hyperparameter tuning.

## Prerequisites

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Bank_data_set_ML_model_development_end_to_end.ipynb
   ```
3. Run the notebook cells sequentially to replicate the analysis.

## Dataset

The dataset used in this project is a CSV file named `corrected_bank_dataset.csv`. It contains various customer attributes and a target variable (`poutcome`), which indicates the outcome of a marketing campaign.

## Author

**Satish Kumar Dwivedi**  
- [LinkedIn](https://www.linkedin.com/in/satish-dwivedi-1291b1227)
