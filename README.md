# Machine-Learning-Projects

## [Employee_Attrition_Prediction & Analysis](https://github.com/Pdjadhav22/Machine-Learning-Projects/blob/master/Employee_Attrition_Prediction%20%26%20Analysis.ipynb)
### Description:
#### Problem Statement
- Need to predict Employee Attrition based on given features.
- Identify Key impacting features.
- Identify target Audience which are more prone to Attrition.

#### Data Pre-Processing
- Basic exploratory analysis and getting insights aabout dataset using the Employee data.
- Insights from exploratory data analysis
- Feature selection using Univariate & Bivariate analysis
- Bivariate Analysis
     - Feature descretization for continuous variables to convert features into bins , using KBinsDiscretizer (10 bins)
     - Analysed each descretised variables with respect to Target variable by plotting against target mean.
     - Feature with visual / observable variations over target mean selected for further analysis.
     - Features showing roughly constant distribution ovet target mean were dropped.

- Using SelectKBest along with chi2 statastics score selected few best features only.
- GradientBoostingClassifier identified as best model with help of GridseaerchCV & Hyper parameter tuning.
- From best model important featured identified.

#### analysis with help of Best model
- With help of prediction probablitieed from beest model, Probability ddecile analysis performed.
- This analysis helped us to come up to conclusion.

#### Conclusion:
- Employees with Low Experience, low Income & working Overtime are most Proned to Attrite
- With information HR team can identify Target Employee to on priority to avoid Attrition


- Performed Feature Selection using Bi-Variate Analysis, SelecktkBest and chi2.
- After evaluating various Algorithms, obtained best results with Gradient Boosting Machine, accuracy- 87.3%.
- Performed Decile Analysis to identify which audience need to be targeted first to reduce chances employee attrition.
