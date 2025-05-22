# 💷 UK Bank Customer Demographics Dashboard

This repository provides an exploratory data analysis and interactive Tableau dashboard for a UK bank's customer demographic data. The goal is to uncover customer distribution patterns across gender, age, job classification, region, and account balances to support targeted financial strategies and segmentation.

## 📁 Repository Contents

- `UK-Bank-Customers.csv`: The main dataset containing personal and financial information of 4,000+ customers from a UK-based bank.
- `UK_Bank_Demographics.twbx`: Tableau workbook that visualizes customer demographics and balance distributions.

## 📄 Dataset Description

This dataset includes 4,014 customer records with the following fields:

| Column Name           | Description                                      |
|------------------------|--------------------------------------------------|
| `Customer ID`         | Unique identifier for each customer              |
| `Name`                | First name of the customer                       |
| `Surname`             | Last name of the customer                        |
| `Gender`              | Gender (Male or Female)                          |
| `Age`                 | Age of the customer                              |
| `Region`              | UK region (England, Wales, Scotland, etc.)       |
| `Job Classification`  | Employment type (e.g., White Collar, Blue Collar)|
| `Date Joined`         | Date the customer joined the bank                |
| `Balance`             | Current account balance (GBP)                    |

## 📊 Key Insights from the Dashboard

The **UK Bank Demographics Dashboard** provides the following insights:

### 🔹 Gender & Age Distribution
- The **customer base is evenly split** across male and female clients.
- **Young professionals (25–40 years)** represent the majority of account holders.

### 🔹 Regional Segmentation
- **England** has the highest concentration of customers, followed by **Scotland** and **Wales**.
- **Northern Ireland** has relatively fewer customers but shows high average balances in certain age groups.

### 🔹 Job Classification Impact
- **White Collar** professionals dominate the dataset and generally maintain **higher average balances**.
- **Blue Collar** customers show more variance in balance, with fewer high-value accounts.

### 🔹 Account Balance Patterns
- High balances are more common among customers aged **40 and above**.
- Some younger clients (under 30) hold significant balances, likely due to early investments or inheritance.

### 🔹 Customer Tenure
- Most customers joined the bank between **2015 and 2016**, indicating a strong acquisition drive during that period.
- Retention appears steady, with balanced distribution across join dates.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/uk-bank-demographics-dashboard.git
