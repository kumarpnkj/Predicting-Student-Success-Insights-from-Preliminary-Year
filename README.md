# Predicting-Student-Success-Insights-from-Preliminary-Year - Logistic Regression Analysis

## Overview

This project aims to predict the success of students in the preliminary year at UMass Dartmouth using logistic regression. The analysis identifies the key factors that contribute to a student's successful completion of the preliminary year and offers insights to improve student support.

The analysis includes:
- Data preprocessing, feature selection, and exploratory data analysis (EDA).
- Building a logistic regression model to predict whether a student will successfully complete the preliminary year.
- Evaluating model performance using various metrics, including accuracy, confusion matrix, and ROC curve.

## Project Structure

- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Jupyter notebooks with detailed analysis, data cleaning, feature selection, model building, and evaluation.
- **images/**: Contains all generated visualizations, including ROC curve plots, feature importance plots, and other EDA visualizations.
- **scripts/**: Python scripts for training the logistic regression model, generating plots, and evaluating model performance.
- **README.md**: Project overview and instructions.

## Key Files

- **notebooks/eda.ipynb**: Exploratory data analysis notebook with detailed feature exploration and visualizations.
- **scripts/logistic_regression.py**: Python script for logistic regression model building and training.
- **scripts/roc_plot_comparison.py**: Script that generates the ROC curves for the full model and reduced model, highlighting the model's performance.
- **images/**: Directory containing the generated visualizations, including the ROC curves, feature importance, and box plots.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

You can install all dependencies using:
```sh
pip install -r requirements.txt
```

### Running the Analysis

1. **Clone the repository**:
   ```sh
   git clone <repository_url>
   cd project-directory
   ```

2. **Run the Jupyter notebooks**:
   Navigate to the `notebooks` directory and open `eda.ipynb` or other related notebooks to view the analysis.

3. **Run scripts**:
   Execute the logistic regression model script by running:
   ```sh
   python scripts/logistic_regression.py
   ```
   To generate the ROC comparison plot:
   ```sh
   python scripts/roc_plot_comparison.py
   ```

## Key Findings

- **Feature Importance**: Key predictors of student success included high school GPA, Pell Grant eligibility, credits earned, and completed community service.
- **Model Performance**: The logistic regression model achieved a mean cross-validation score of ~0.86. The ROC curves for the full and reduced models indicate strong model performance.

### Figures
- **Figure 9**: Boxplot of S18 GPA
- **Figure 10**: ROC Curve for Full Model
- **Figure 11**: ROC Curve for Reduced Model

## Discussion
The findings indicate that academic performance and financial support are major factors in student retention. By addressing these factors, the university can design targeted support to enhance student success in the preliminary year.

## Future Improvements
- Incorporate additional data, such as socio-economic background or support received throughout the year, to improve the model's predictive power.
- Explore other machine learning models (e.g., random forests, boosting algorithms) to compare performance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- **UMass Dartmouth** for providing the data.

