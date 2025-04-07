
# Insurance Fraud Detection using Machine Learning and Tableau

This project focuses on detecting fraudulent insurance claims using a real-world dataset containing over 1,000 records and 40+ features, including claim details, customer profiles, and incident metadata. The objective was to build interpretable machine learning models and interactive dashboards to identify patterns in fraudulent behavior.

## Project Highlights

- Built classification models using Logistic Regression, Random Forest, XGBoost, and Ensemble Voting
- Applied SMOTE for class imbalance handling
- Performed preprocessing with SimpleImputer and StandardScaler
- Evaluated models using confusion matrix, classification report, and fraud probability scores
- Interpreted feature importance to identify fraud risk drivers
- Designed interactive Tableau dashboards featuring:
  - Fraud distribution by state
  - Claim severity by incident type
  - Fraud rate by vehicle make
  - Filters for incident type, region, and auto make
## Tools and Technologies

- Python (Pandas, scikit-learn, XGBoost, imbalanced-learn)
- Tableau Public
- Google Colab
- Git and GitHub

## Tableau Dashboard

View the published dashboard on Tableau Public:  
**[Link to Tableau Dashboard]** 
#(https://public.tableau.com/)

## Key Insights

- Fraud claims show geographic concentration in select states
- Fraudulent claims differ in age and claim amount distributions

## Getting Started

1. Clone the repository  
2. Run the Jupyter notebook to reproduce the model training  
3. Export predictions and load into Tableau for visualization

## License

This project is open-source and available for educational use.
