# Churn Prediction on Kaggle

## Project Overview

This project aims to predict customer churn using data from a Kaggle competition. The objective is to develop a predictive model that can identify at-risk customers and help businesses retain them.

## Competition Details

- **Platform:** Kaggle
- **Competition:** Churn Prediction
- **Link to Competition:** [Kaggle Churn Prediction](https://www.kaggle.com/c/churn-prediction)

## Repository Structure
```pre
├── data
│ ├── raw_data.csv
│ ├── processed_data.csv
├── notebooks
│ ├── EDA.ipynb
│ ├── Model_Baseline.ipynb
│ ├── Model_Improvement.ipynb
├── scripts
│ ├── preprocess.py
│ ├── train.py
│ ├── evaluate.py
├── results
│ ├── baseline_submission.csv
│ ├── improved_submission.csv
├── README.md
└── requirements.txt
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

### Installation

1. Clone the repository
    ```bash
    git clone https://github.com/username/churn-prediction.git
    ```
2. Navigate to the project directory
    ```bash
    cd churn-prediction
    ```
3. Install required packages
    ```bash
    pip install -r requirements.txt
    ```

## Data Analysis and Preprocessing

- **Data Overview:** The dataset includes customer demographics, account information, and usage patterns.
- **Preprocessing Steps:**
  - Handled missing values using imputation techniques.
  - Performed feature engineering to create new variables.
  - Scaled numerical features for better model performance.

## Model Implementation

### Baseline Model

- **Algorithm:** Logistic Regression
- **Results:** Achieved a baseline accuracy of 78%.

### Advanced Models

- **Algorithms:** Random Forest, XGBoost, and Neural Networks
- **Hyperparameter Tuning:** Used Grid Search and Random Search for optimization.
- **Results:** Improved accuracy to 85% with XGBoost after tuning.

## Submissions and Leaderboard Progress

- **Submission 1:** Logistic Regression - Baseline accuracy of 78%.
- **Submission 2:** Random Forest - Improved accuracy to 82%.
- **Submission 3:** XGBoost - Further improved accuracy to 85%.
- **Proof of Submissions:** Screenshots of submission trials and leaderboard rankings are included in the GitHub repository.

## Lessons Learned

1. **Algorithms Tried and Rationale:**
   - **Logistic Regression:** Chosen for its simplicity and interpretability.
   - **Random Forest:** Selected for its ability to handle non-linear relationships and importance ranking of features.
   - **XGBoost:** Utilized for its powerful boosting technique that improves model performance.

2. **Potential Improvements:**
   - Explore additional feature engineering techniques.
   - Implement ensemble methods combining multiple models.
   - Allocate more time for hyperparameter tuning and model validation.

## Repository Link

- [GitHub Repository](https://github.com/username/churn-prediction)
- **Competition Link:** Included in the README file of the repository.

## References

- [Kaggle Competitions](https://www.kaggle.com/docs/competitions)
- [Kaggle Getting Started](https://www.kaggle.com/code/alexisbcook/getting-started-with-kaggle-competitions)
- [Zindi Competitions](https://zindi.africa/learn/how-to-enter-your-first-zindi-competition)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


