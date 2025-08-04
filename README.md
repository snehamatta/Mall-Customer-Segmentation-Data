 Mall Customer Segmentation – Data Cleaning

This project focuses on cleaning and preparing the Mall Customer Segmentation Dataset using Python and Pandas. The dataset includes customer demographic and spending behavior data collected from a mall. The objective was to fix formatting issues, ensure data consistency, and prepare the dataset for future analysis or modeling tasks.

---

Objective

To clean the raw dataset by:
- Fixing inconsistent column names
- Standardizing textual data (e.g., gender)
- Verifying data types
- Checking for missing and duplicate values
- Exporting a clean .csv file for analysis

---

Tasks Performed

- Renamed column headers to lowercase with underscores
- Cleaned and standardized the gender column (lowercased, stripped whitespace)
- Verified all numerical columns (age, annual_income, spending_score) are integers
- Confirmed that there were no missing or duplicate values
- Exported the cleaned data to a new `mall_customers_cleaned.csv file

---

Files Included

| File | Description |

| Mall_Customers.csv | Original raw dataset |
| mall_customer_cleaning.ipynb | Jupyter Notebook containing full cleaning code |
| mall_customers_cleaned.csv | Cleaned dataset exported in CSV format |
| README.md | Project summary and documentation |

---

 Tools Used

- Python
- Pandas 
- Jupyter Notebook  
- openpyxl (only installed, not used — Excel export was skipped)

---

Skills Demonstrated

- Real-world data cleaning
- Using .isnull(), .duplicated(), .str.strip(), .astype(), and .to_csv() in Pandas
- Exporting and verifying cleaned data
- Creating clear and organized documentation for reproducibility

---

Outcome

The final dataset is now clean, consistent, and ready for use in customer segmentation, clustering models, or visualization dashboards.

This task was completed as part of a data analyst internship assignment focused on understanding the core fundamentals of preprocessing real-world datasets.

---

