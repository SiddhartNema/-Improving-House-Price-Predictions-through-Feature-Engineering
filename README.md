# -Improving-House-Price-Predictions-through-Feature-Engineering

This project focuses on improving house price predictions by applying **feature engineering techniques** such as missing value handling, encoding, transformations, and feature importance analysis.

## 🎯 Objective
Enhance model performance using:
- Handling missing values
- Encoding categorical variables (LabelEncoder, One-Hot)
- Log transformation of skewed data
- Feature selection using Random Forest

## 🛠 Tools & Libraries
- Python (Jupyter Notebook)
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (RandomForest, LabelEncoder, Linear Regression)

## 📈 Key Steps
- 🔍 Identified missing values with `df.isnull().sum()`
- 🧹 Cleaned and transformed skewed features using `np.log1p()`
- 🔤 Encoded categorical variables
- 🧠 Evaluated feature importance using `.feature_importances_`
- 📊 Trained and tested a regression model

## 📊 Model Output
- Visual feature importance plot
- RMSE performance evaluation

## 🚀 How to Run
1. Clone the repo  
2. Open `house_price_prediction.ipynb`  
3. Run the notebook cells sequentially  
4. Make sure to install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
