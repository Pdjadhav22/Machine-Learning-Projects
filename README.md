# Machine-Learning-Projects

## [1. Employee_Attrition_Prediction & Analysis](https://github.com/Pdjadhav22/Machine-Learning-Projects/blob/master/Employee_Attrition_Prediction%20%26%20Analysis.ipynb)
### Problem Statement
- Need to predict Employee Attrition based on given features.
- Identify Key impacting features.
- Identify target Audience which are more prone to Attrition.

### Data Pre-Processing
- Basic exploratory data analysis and getting insights about dataset using Employee data.
- Feature selection using Univariate & Bivariate analysis
- Bivariate Analysis
     - Feature descretization for continuous variables to convert features into bins , using KBinsDiscretizer (10 bins)
     - Analysed each descretised variables with respect to Target variable by plotting against target mean.
     - Features with observable variations over target mean selected for further analysis, rest dropped.
- Using SelectKBest along with chi2 statastics score selected few best features only.
- GradientBoostingClassifier identified as best model with help of GridseaerchCV & Hyper parameter tuning.
- From best model important featured identified.

### Analysis based on Best model
- With help of predict_probabolity from best model, Probability decile analysis was performed.
- This analysis helped us to come up to below conclusion.

### Conclusion:
- Employees with Low Experience, low Income & working Overtime are most Proned to Attrite
- With information HR team can identify Target Employee to on priority to avoid Attrition



## [2. Vehicle-loan-default-prediction](https://github.com/Pdjadhav22/Machine-Learning-Projects/blob/master/vehicle-loan-default-prediction.ipynb)
### Problem Statement
- To identify probable Vehicle Loan Defaulter based on input dataset.

### Description
- Basic exploratory data analysis and getting insights about dataset using Employee data.
- Bassed of EDA, few Feature Engeening performed, like, Date of birth converted to age, no. of inactive accounts is difference of total & active accounts
- Missing values & few incorrect values imputed with mean values.
- Data scaled before training using RobustScalar.
- SMOTE from imblearn.over_sampling used to handle imbalanced dataset.
- Train & Test featured distribution checked against repective feature, to observe of diffrnece between .
- Model with best Recall score selected - XGBoost (Recall score = 0.86)
