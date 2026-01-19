# Machine-Learning-CodeBasics

## 🧠 What You Learn From These Notebooks (Code-Level - Basic Regression, Train Test Splits & Performance Metrics)

This section lists **only what is actually implemented in code** across the notebooks — no theory fluff.

---

### Data Loading & Inspection (pandas)
- Loading CSV data using `pandas.read_csv`
- Inspecting datasets using `.head()`
- Checking missing values with `.isna().sum()`

---

### Feature & Target Preparation
- Separating features (`X`) and target variable (`y`)
- Understanding how column selection affects model inputs

---

### Train–Test Split (scikit-learn)
- Splitting data using `train_test_split`
- Controlling split ratio with `test_size`
- Ensuring reproducibility using `random_state`
- Creating `X_train`, `X_test`, `y_train`, `y_test`

---

### Linear Regression Modeling
- Initializing `LinearRegression`
- Fitting a model using `.fit()`
- Inspecting learned parameters:
  - Model coefficients (`coef_`)
  - Model intercept (`intercept_`)

---

### Predictions
- Generating predictions on test data using `.predict()`

---

### Model Evaluation Metrics
- Evaluating regression performance using:
  - `r2_score`
  - `mean_squared_error`
- Interpreting numeric model performance outputs

---

### Notebook Hygiene
- Suppressing warnings for cleaner outputs
- Executing a full ML workflow end-to-end in a notebook

---

## 🛠 Tech Stack Used
- Python
- pandas
- scikit-learn
- Jupyter Notebook
- uv (for environment management)
