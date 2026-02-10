# Job Applications Data Analysis (2023)

## 📌 Project Overview
This project analyzes job application data collected by a recruiting agency during the year 2023. The goal of the analysis is to summarize application trends on a monthly basis in order to support data-driven decisions for optimizing the agency’s online application process.

The analysis was completed as part of the **Google Data Analytics Professional Certificate** on Coursera.

---

## 🎯 Objectives
The analysis focuses on answering the following questions:
- What was the total number of applications received each month?
- How many applications were received in total during the year?
- Which months had the lowest and highest number of applications?
- What was the average number of applications received per month?

---

## 🛠 Tools & Techniques
- Google Sheets
- Spreadsheet functions: `TEXT`, `COUNTIF`, `SUM`, `MIN`, `MAX`, `AVERAGE`
- Sorting data by date
- Creating a custom summary data table
- Data formatting for clarity and presentation

---

## 📂 Dataset Description
The dataset contains job application records with the following columns:
- **Applicant ID**: Unique identifier for each applicant
- **Date**: Date and time when the application was submitted
- **Job Title**: Position applied for
- **Job Location**: Location of the job
- **Hired**: Indicates whether the applicant was hired (TRUE/FALSE)
- **Easy Apply**: Indicates if the application was submitted directly through the website

---

## 🔍 Analysis Process

### 1. Data Preparation
- Renamed the spreadsheet and raw data sheet for clarity
- Adjusted column widths for better readability
- Sorted the dataset by date in ascending order to analyze trends chronologically

### 2. Month Extraction
- Created a new column using the `TEXT` function to extract the month from the application date:
=TEXT(B2,"mmmm")
- Applied the formula to all rows to label each application by month

### 3. Custom Data Table
- Created a summary table listing all months from January to December
- Used the `COUNTIF` function to calculate the number of applications received each month:
=COUNTIF('raw data'!G:G, A2)

### 4. Key Calculations
- **Total applications (yearly)**:
=SUM(B2:B13)
- **Lowest monthly applications**:
=MIN(B2:B13)
- **Highest monthly applications**:
=MAX(B2:B13)

- **Average applications per month**:


=AVERAGE(B2:B13)


---

## 📊 Key Findings
- A total of **32,596 applications** were received in 2023.
- The month with the **lowest number of applications** was **February**.
- The month with the **highest number of applications** was **July**.
- On average, the agency received approximately **2,716 applications per month**.

---

## 💡 Insights & Recommendations
- February represents a slow period for applications, suggesting an opportunity to increase advertising and outreach efforts during this month.
- July shows peak application activity, indicating strong seasonal demand.
- Understanding monthly trends can help the agency allocate resources more effectively and improve the performance of its online application process.

---

## 📈 Skills Demonstrated
- Spreadsheet-based data analysis
- Use of functions to summarize large datasets
- Analytical thinking and trend identification
- Data organization and presentation
- Translating data into actionable business insights

---

## 👤 Author
**Ayah Alharazin**

---

## 📎 Notes
This project demonstrates foundational spreadsheet skills essential for data analysts and serves as a building block for more advanced analysis using tools such as SQL and Python.

