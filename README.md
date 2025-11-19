# 📊 Salary Analysis Using Python (EDA Project)

This project performs Exploratory Data Analysis (EDA) on the Salaries.csv dataset.
The goal is to understand employee salary distribution, clean the dataset, extract insights, and perform analysis such as identifying top earners, common job titles, and missing data patterns.

## 🧰 Tools & Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## 📘 Dataset Description

The dataset contains the following important columns:
- EmployeeName
- JobTitle
- BasePay
- OvertimePay
- Benefits
- TotalPay
- TotalPayBenefits
- Year
- Agency
- Status


## 🔍 What This Project Does
**1. Import Libraries**

Loaded Pandas and other libraries needed for analysis.

 **2. Load the Dataset**
```python
data = pd.read_csv("Salaries.csv")
```

**3. Explore Data**

- data.head()

- data.tail()

- Shape (rows, columns)

- Data types & memory info

**4. Data Cleaning**

- Cleaning steps performed:

- Dropped unnecessary columns:

```python
["Id", "Notes", "Agency", "Status"]
```


- Converted columns to numeric (ex: BasePay)

- Checked and removed rows with excessive null values

- Handled missing data

**5. Data Analysis Covered**

- Find Job Title of ALBERT PARDINI

- Find how much salary (with benefits) he earns

- Display person with highest BasePay

- Top 5 most common job titles

- Count of unique job titles

- Salary distribution analysis

- Handling inconsistent data types

## 📈 Key Insights You Can Extract

- Who earns the highest salary in the dataset

- Which job titles are the most common

- Base pay vs. total pay comparisons

- Outliers in employee salaries

- Missing data patterns

 -Year-wise salary details (if used)
