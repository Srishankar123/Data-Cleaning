# 🧹 Data Cleaning in SQL – Layoffs Dataset

This repository contains a comprehensive **data cleaning project using SQL**, performed on the [Layoffs dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022) from Kaggle. The goal of this project is to prepare raw, inconsistent layoff data into a clean and analysis-ready format using **SQL Server**.

---

## 📁 Files Included

- `layoffs.sql` – SQL script with step-by-step cleaning operations
- `raw_layoffs.csv` – Original dataset (as downloaded from Kaggle)
- `cleaned_layoffs_view.sql` – Final view or cleaned table query
- `README.md` – Project documentation

---

## 🧠 Objective

To apply **data cleaning techniques in SQL** on a real-world dataset and transform messy data into a structured, reliable dataset that can be used for analysis, dashboards, or business decision-making.

---

## 🧰 Tools Used

- **SQL Server / SSMS**
- **Kaggle Layoffs Dataset**
- **Data Cleaning Techniques**
  - Trimming whitespace
  - Handling null and duplicate values
  - Unifying inconsistent data entries
  - Creating views for cleaned output

---

## 🧼 Key Cleaning Steps Performed

1. **Removed Duplicates**  
   - Identified and deleted exact duplicate rows using `ROW_NUMBER()`.

2. **Standardized Column Values**  
   - Cleaned up inconsistent company names and industry formats.
   - Fixed formatting issues with text casing and spacing.

3. **Null Handling**  
   - Replaced or flagged null values in critical columns like `total_laid_off` and `percentage_laid_off`.

4. **Converted Date Formats**  
   - Fixed issues with inconsistent or invalid date values in the `date` column.

5. **Removed Irrelevant Data**  
   - Filtered out rows with missing company names or key numerical data.

6. **Created a Clean View**  
   - Combined all cleaning steps into a final `CREATE VIEW` statement for easy querying.

---

## 📊 Outcome

The result is a **cleaned and normalized dataset** that can now be used for:
- Visual dashboards (Power BI, Tableau, etc.)
- Trend analysis of layoffs by year, industry, and region
- Exploratory data analysis or predictive modeling

---

## 🔗 Useful Links

- 🌐 [Portfolio Website](https://srishankar.netlify.app/)
- 💼 [LinkedIn Profile](https://linkedin.com/in/srishankar-lokanath-99a5b4252)
- 📬 Email: [srishankarloknath@gmail.com](mailto:srishankarloknath@gmail.com)

---

## ⭐️ If you found this project helpful

Feel free to star 🌟 the repository or fork 🍴 it. Feedback and suggestions are welcome!

