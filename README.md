# Carbon-Emission

## ✅ Highlights of Data Cleaning Improvements

The notebook `1_data_preparation_cleaned.ipynb` includes several enhancements over the original preparation process to ensure the dataset is analysis-ready:

### 🔍 1. Missing Value Detection
- Identified missing values across all columns using `isnull().sum()`.
- Helps in making informed decisions on imputation or deletion.

### 🧹 2. Dropping Empty Rows
- Removed rows where **all values are missing** to reduce noise and memory usage.

### ♻️ 3. Removing Duplicates
- Detected and removed **duplicate rows** to improve data quality and model reliability.

### 🏷️ 4. Column Name Normalization
- Reformatted all column names to be lowercase, space-free, and consistent.
- Enhances usability and avoids syntax issues in analysis and modeling.

### 🔢 5. Data Type Conversion
- Converted applicable columns to numeric types using `pd.to_numeric()`.
- Ensures compatibility with mathematical operations and ML models.

### 💾 6. Saved Cleaned Dataset
- Exported the cleaned dataset to `cleaned_climate_data.csv` for future use in EDA and modeling.

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Jupyter Notebook

## 📌 Credits
This work is developed as part of the **AICTE Internship (June 2025)** initiative of Edunet Foundation.



