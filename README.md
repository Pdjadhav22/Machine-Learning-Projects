# Machine-Learning-Projects

## [Employee_Attrition_Prediction & Analysis](https://github.com/Pdjadhav22/Machine-Learning-Projects/blob/master/Employee_Attrition_Prediction%20%26%20Analysis.ipynb)
### Description:
#### Problem Statement
- Need to predict Employee Attrition based on given features.
- Identify Key impacting features.
- Identify target Audience which are more prone to Attrition.

#### Data Pre-Processing
- Basic exploratory data analysis and getting insights about dataset using Employee data.
- Feature selection using Univariate & Bivariate analysis
- Bivariate Analysis
     - Feature descretization for continuous variables to convert features into bins , using KBinsDiscretizer (10 bins)
     - Analysed each descretised variables with respect to Target variable by plotting against target mean.
     - Features with observable variations over target mean selected for further analysis, rest dropped.
- Using SelectKBest along with chi2 statastics score selected few best features only.
- GradientBoostingClassifier identified as best model with help of GridseaerchCV & Hyper parameter tuning.
- From best model important featured identified.

#### Analysis with help of Best model
- With help of predict_probabolity from best model, Probability decile analysis performed.
- This analysis helped us to come up to below conclusion.

#### Conclusion:
- Employees with Low Experience, low Income & working Overtime are most Proned to Attrite
- With information HR team can identify Target Employee to on priority to avoid Attrition
