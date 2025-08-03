# 🔍 Beginner Explanation – Heart Disease ML Project

## Step-by-Step Breakdown

### Step 1: Load Dataset
We read the CSV file into a pandas DataFrame to explore the data.

### Step 2: Data Cleaning
We check for missing values, and all data is already numeric (no need for encoding here).

### Step 3: Split Features and Labels
We separate features (X) from the target variable (y).

### Step 4: Train-Test Split
We split the data using `train_test_split` for proper model evaluation.

### Step 5: Train Model
We use `LogisticRegression()` to train a classification model.

### Step 6: Evaluate
Accuracy, confusion matrix, and classification report give us insight into model performance.

### Step 7: Predict New Data
We test the model with a new, manual input to simulate real-world prediction.

---

💡 Want to go deeper? Try using Random Forest, StandardScaler, and ROC-AUC next!
