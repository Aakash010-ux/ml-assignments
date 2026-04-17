# ML Workflow Assignment

## Task 1

**Label Column:**  
repeat_purchase_flag  
Justification: This column is the target variable that indicates whether a customer made a repeat purchase within 30 days.

**Data Leakage Column:**  
discount_used_on_repeat_order  
Justification: This column contains information about the repeat purchase itself, which would not be available at prediction time and can cause data leakage.

---

## Task 2

**Step 1: Data Preprocessing (Cleaning & Feature Preparation)**  
Why it matters: It ensures the dataset is clean and usable by handling missing values, outliers, and proper formatting.

**Step 2: Exploratory Data Analysis (EDA)**  
Why it matters: It helps understand patterns, relationships, and important features before building a model.