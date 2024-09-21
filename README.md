# 🏠 Insurance Claim Prediction 

This project aims to build a predictive model to determine whether a building will experience an accident during the insurance period. The goal is to provide personalized insurance contract offers based on this model. 🏢💼 

## 📁 Dataset 

We are provided with the `train_insurance.csv` dataset, which contains 5012 observations described by 12 attributes, including the target variable `claim`. The target variable indicates whether a claim was made (`1` for yes, `0` for no). 

## 🚀 Project Overview 

1. **Data Preprocessing** 🛠️ 
 
- Loaded the dataset and performed initial cleaning.  
- Filled missing data and removed unnecessary columns.  
- Detected and removed outliers using boxplots 📊.  
- Removed duplicate records for a cleaner dataset. 
 
2. **Encoding and Visualization** 🔍 
 
- Applied ordinal encoding to transform categorical variables into numerical values.  
- Created a heatmap to visualize correlations between features 🔥. 
 
3. **Data Splitting** ✂️ 
 
- Split the data into training, validation, and test sets for model development and evaluation. 
 
4. **Modeling** 🧠 
 
- Utilized the `DecisionTreeClassifier` to predict the likelihood of a building having an accident during insurance period. 

 
## 🔧 Tools Used 

 
- **Pandas** for data manipulation  
- **Matplotlib/Seaborn** for data visualization  
- **Scikit-learn** for modeling and evaluation 
- **NumPy** for numerical computations 
 
## 📝 Results 

 
The model aims to provide a high level of accuracy in predicting insurance claims, helping insurance companies better tailor their contracts to customers' risk profiles.
