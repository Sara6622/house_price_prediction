# 🏠 House Price Prediction

This project is a machine learning pipeline for predicting house prices using structured data. It was built as part of my learning journey in machine learning and covers data preprocessing, feature engineering, and model training.

## 📊 Dataset

The dataset is taken from a house pricing problem and consists of two CSV files:

- `train.csv`: Contains training data with the target variable (`SalePrice`)
- `test.csv`: Contains test data to evaluate the model

## 🧰 Tools and Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Pipeline, Imputer, Linear Regression, etc.)

## 📌 Project Workflow

1. **Load Data**
2. **Handle Missing Values**
   - Drop columns with more than 30% missing
   - Fill numeric values with median
   - Fill categorical values with mode
3. **Feature Engineering**
   - Separate numerical and categorical features
   - Use `SimpleImputer`, `StandardScaler`, and `OneHotEncoder` in a pipeline
4. **Modeling**
   - Train a Linear Regression model
   - Evaluate with Mean Squared Error (MSE) and R² score

## 📈 Model Evaluation

The performance of the linear regression model was measured using:

- **Mean Squared Error (MSE)**
- **R² Score**

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

# Run the notebook
jupyter notebook price.ipynb
