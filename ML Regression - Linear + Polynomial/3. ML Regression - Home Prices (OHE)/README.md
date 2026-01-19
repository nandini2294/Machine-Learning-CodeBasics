## 🧠 What You Learn From This Notebook (Code-Level: One-Hot Encoding)

This notebook focuses on handling **categorical variables** and building a regression model using encoded features.

---

### Data Loading & Inspection (pandas)
- Loading CSV data using `pandas.read_csv`
- Inspecting the dataset structure and values

---

### One-Hot Encoding (pandas)
- Converting categorical columns using `pd.get_dummies`
- Encoding the `locality` column into binary indicator variables
- Using `drop_first=True` to avoid the dummy variable trap
- Verifying encoded output using `.sample()`

---

### Feature & Target Preparation
- Selecting numerical and encoded categorical columns as features
- Separating:
  - Features (`X`)
  - Target variable (`y`)

---

### Train–Test Split (scikit-learn)
- Splitting data using `train_test_split`
- Creating `X_train`, `X_test`, `y_train`, `y_test`

---

### Linear Regression Modeling
- Initializing a `LinearRegression` model
- Training the model using `.fit()`
- Evaluating model performance using `.score()` on test data

---

### Making Predictions on New Data
- Creating a custom `DataFrame` matching the encoded feature schema
- Manually specifying one-hot encoded locality values
- Generating predictions using `.predict()`

---

### Notebook Workflow
- Executing a complete regression pipeline:
  - Data loading
  - Encoding
  - Training
  - Evaluation
  - Prediction
