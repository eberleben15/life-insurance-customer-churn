# Life Insurance Customer Churn Analysis with Deep Learning

## Project Overview
This project analyzes customer churn in the life insurance industry using deep learning techniques. The goal is to identify complex patterns in customer behavior that lead to attrition and provide data-driven recommendations for reducing churn.

## Dataset
The dataset includes customer information, claim details, premium amounts, and churn status for a life insurance company. Key features include:
- Customer demographic information
- Claim amounts and reasons
- Premium categories and amounts
- Data confidentiality levels
- Claim request outcomes
- BMI values

## Analysis Approach
1. **Exploratory Data Analysis (EDA)** - Visualizing churn distribution and relationships with key features
2. **Feature Engineering** - Preparing data for neural networks with appropriate transformations
3. **Deep Learning Model** - Building and training a neural network with multiple hidden layers
4. **Model Evaluation** - Assessing performance and interpreting the model's predictions
5. **Business Insights** - Translating deep learning findings into actionable recommendations

## Key Findings
- Neural networks effectively identify complex patterns in customer behavior that lead to churn
- Claim-to-premium ratio is a significant predictor of customer attrition
- Data confidentiality level impacts customer retention
- Deep learning captures both linear and non-linear relationships in the data
- Model identifies high-risk customers with high precision for targeted interventions

## Repository Structure
- `life_insurance_churn_analysis.ipynb`: Main analysis notebook with deep learning implementation
- `data/life_insurance_churn.csv`: Dataset containing customer and insurance information
- `README.md`: Project documentation

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- tensorflow
- scikit-learn
- shap (optional, for model interpretability)

## Getting Started
1. Clone this repository
2. Install required packages: `pip install pandas numpy matplotlib seaborn tensorflow scikit-learn shap`
3. Open and run `life_insurance_churn_analysis.ipynb`
