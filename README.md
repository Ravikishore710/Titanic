# 🚢 Titanic Classification - Machine Learning Project

This project focuses on predicting survival outcomes from the Titanic dataset using machine learning techniques. The workflow includes data preprocessing, feature engineering, pipeline construction, model training, and evaluation using cross-validation.

## 📂 Project Structure

- `Titanic-classification.ipynb`: Complete notebook with data loading, preprocessing, modeling, and evaluation steps.
- `train.csv`, `test.csv`: Standard Titanic dataset files.
- Preprocessing: Pipelines built using `ColumnTransformer`, `SimpleImputer`, `StandardScaler`, and `OneHotEncoder`.

## 🔧 Tools & Libraries Used

- Python (Pandas, NumPy)
- Scikit-learn (Pipeline, ColumnTransformer, RandomForestClassifier, cross_val_score)
- Jupyter Notebook

## 📊 Methodology

1. **Data Cleaning**:
   - Handled missing values using `SimpleImputer`.
   - Applied scaling to numerical features and one-hot encoding to categorical ones.

2. **Pipeline Construction**:
   - Created separate pipelines for numerical and categorical features.
   - Combined using `ColumnTransformer` for a clean and reproducible preprocessing setup.

3. **Modeling**:
   - Trained a `RandomForestClassifier`.
   - Evaluated using 10-fold cross-validation with `cross_val_score`.

4. **Performance Metric**:
   - Average accuracy across 10 folds was used to assess model performance.

## ✅ Results

- Achieved robust accuracy using cross-validation, ensuring the model's generalizability.
- Modular pipeline design makes it easy to swap models or add new preprocessing steps.
- ![image](https://github.com/user-attachments/assets/192d32df-22aa-4376-8702-a86dec33d263)


## 📎 How to Run

1. Clone the repository.
2. Ensure `train.csv` and `test.csv` are in the correct folders.
3. Open `Titanic-classification.ipynb` in Jupyter or Colab.
4. Run all cells to preprocess the data and evaluate the model.

## 📈 Future Work

- Try other classifiers like XGBoost or SVM.
- Perform hyperparameter tuning using `GridSearchCV`.
- Explore feature importance and SHAP values.

---

🔗 **Check out the notebook for full details!**  
