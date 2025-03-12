<<<<<<< HEAD
# WHO-COVID19-DataCleaning
This project focuses on data cleaning and preprocessing using the WHO COVID-19 dataset. It includes handling missing values, removing duplicates, and ensuring data consistency for analysis. The repository contains Jupyter notebooks, Python scripts, and a final report documenting the entire process. 🚀 
=======
# Data Cleaning for WHO COVID-19 Dataset

## 📌 Project Overview
This project focuses on cleaning and preprocessing the **WHO COVID-19 Global Daily Data** dataset. The dataset contains information about daily COVID-19 cases, deaths, and other attributes. The goal of this project is to handle missing values, remove inconsistencies, and ensure the dataset is suitable for analysis.

## 📂 Dataset Description
- **Source**: World Health Organization (WHO)
- **File**: `WHO-COVID-19-global-daily-data.csv`
- **Columns:**
  - `Date_reported`: The date of the report.
  - `Country_code`: The two-letter country code.
  - `Country`: The full name of the country.
  - `WHO_region`: The WHO region for the country.
  - `New_cases`: The number of newly reported COVID-19 cases.
  - `Cumulative_cases`: The total number of reported cases till that date.
  - `New_deaths`: The number of newly reported deaths.
  - `Cumulative_deaths`: The total number of reported deaths till that date.

## ⚙️ Data Cleaning Steps
### 1️⃣ Exploratory Data Analysis (EDA)
- Checked for **missing values** in `Country_code`, `New_cases`, and `New_deaths`.
- Identified **0 duplicate rows**.
- Checked for **incorrect data types** and confirmed all columns are in the correct format.

### 2️⃣ Handling Missing Values
- `Country_code`: Missing values replaced with **"Unknown"**.
- `New_cases` & `New_deaths`: Missing values replaced with **0**.

### 3️⃣ Data Export
- Saved the cleaned dataset as `WHO-COVID-19-cleaned.csv` in the `data/processed/` folder.

## 📊 Visualizations & Insights
- **Distribution of COVID-19 cases:** A histogram was created to analyze the distribution of daily cases.
- **Missing Value Heatmap:** A heatmap was generated before and after cleaning to verify the completeness of the dataset.

## 🚀 Project Structure
```
Data_Cleaning_Project/
│── data/
│   ├── raw/  → (Original dataset)
│   ├── processed/  → (Cleaned dataset)
│── notebooks/
│   ├── data_cleaning.ipynb  → (Jupyter Notebook with code & analysis)
│── reports/
│   ├── data_cleaning_report.pdf  → (Final Report)
│── README.md  → (Project Overview)
│── requirements.txt  → (Libraries needed)
```

## 🔧 Installation & Dependencies
To run this project, install the required libraries:
```sh
pip install pandas numpy matplotlib seaborn
```

## 📥 How to Use the Data
- The cleaned dataset (`WHO-COVID-19-cleaned.csv`) can be used for further analysis, visualization, or machine learning models.
- The `data_cleaning.ipynb` notebook provides step-by-step data preprocessing.

## 🌟 Key Takeaways
- Missing values were handled appropriately to avoid data inconsistencies.
- The dataset is now **clean, structured, and analysis-ready**.
- This cleaning process ensures accuracy and reliability in COVID-19 data reporting.

## 📌 Next Steps
- Perform deeper analysis on trends in COVID-19 cases and deaths.
- Apply machine learning models for predictions.

## 📢 About the Author
This project was completed by **Syed Habib Haider**, a Data Analyst specializing in data cleaning, visualization, and analysis.

---
✅ **If you found this project helpful, feel free to ⭐ the repository!**
>>>>>>> 8cb6253 (Initial commit - Uploaded WHO COVID-19 Data Cleaning Project)
