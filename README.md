# 💷 UK Bank Customer Demographics Dashboard

This repository provides an exploratory data analysis and interactive Tableau dashboard for a UK bank's customer demographic data. The goal is to uncover customer distribution patterns across gender, age, job classification, region, and account balances to support targeted financial strategies and segmentation.

## 🎯 Objective

This project enables data-driven segmentation and strategy formulation for banks through clear demographic and financial profiling of their customer base.

## 📁 Repository Contents

- `UK-Bank-Customers.csv`: The main dataset containing personal and financial information of 4,000+ customers from a UK-based bank.
- `UK_Bank_Demographics.twbx`: Tableau workbook that visualizes customer demographics and balance distributions.
  - An **interactive dashboard** with dynamic filters.
  - A **storyline** guiding users through key demographic and financial insights.

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

### 📌 Dashboard Features
The **interactive dashboard** allows stakeholders to:
- Filter by **Region**, **Gender**, and **Job Classification**
- Compare **average balances** by age group
- Visualize customer distribution across regions
- Identify high-value customer segments

### 📖 Storyline Highlights
The **storyline** walks the viewer through five key questions:
1. **What is the demographic composition of our customers?**
2. **Which regions have the highest account balances?**
3. **How does job type affect financial behavior?**
4. **Are older customers wealthier on average?**
5. **What was the customer acquisition trend over time?**

This guided narrative simplifies insight discovery and provides an executive summary of findings.

## 📊 Key Insights

### 🔹 Gender & Age Distribution
- The dataset is almost evenly split between **male** and **female** clients.
- **Young professionals (25–40 years)** form the largest customer segment.

### 🔹 Regional Segmentation
- **England** has the highest customer density.
- **Northern Ireland** has fewer customers but shows **notably high average balances** in select groups.

### 🔹 Job Classification
- **White Collar** professionals dominate and maintain higher average balances.
- **Blue Collar** customers show greater balance variance and fewer high-net accounts.

### 🔹 Balance Distribution by Age
- Customers **aged 40+** hold higher average balances.
- Some **under-30 customers** also maintain high balances, likely due to inheritance or early investments.

### 🔹 Customer Tenure
- Most accounts were opened during **2015–2016**, reflecting a strong acquisition phase.
- A balanced tenure distribution suggests good customer **retention**.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Anaghar27/UK-Bank-Customer-Demographics-Dashboard-using-Tableau.git

2. Open the Tableau workbook:
- File: UK_Bank_Demographics.twbx
- Software: Tableau Desktop or Tableau Public

3. Explore:
- Dashboard tabs for exploratory analysis
- Storyline tab for guided, executive-friendly insights
