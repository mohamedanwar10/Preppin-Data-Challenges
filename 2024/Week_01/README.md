# 2024 - Week 1: Prep Air's Flow Card  

## Challenge Description  
[Click here for full details](https://preppindata.blogspot.com/2024/01/2024-week-1-prep-airs-flow-card.html).  

**Goal:** Clean flight data and separate passengers into Flow Card holders and non-holders.  

### Data Cleaning Steps:  
- Split the **Flight Details** field into:
  - **Date**  
  - **Flight Number**  
  - **From**  
  - **To**  
  - **Class**  
  - **Price**  
- Convert data types:
  - **Date** → Date format  
  - **Price** → Decimal  
  - **Flow Card** → Yes/No instead of 1/0  
- Create two datasets:
  - One for **Flow Card holders**  
  - One for **Non-Flow Card holders**  
- Export the results.  

## Files  
- `data.csv` → The dataset.  
- `solution.xlsx` → My solution in Excel.  

## Solution Approach  
- **Step 1:** Load the dataset into Excel.  
- **Step 2:** Split the **Flight Details** field using Excel functions (`TEXT`, `MID`, etc.).  
- **Step 3:** Convert data types using Excel formatting tools.  
- **Step 4:** Filter and create two datasets based on the **Flow Card** value.  
- **Step 5:** Save and export the final datasets as separate CSV files.  

---

### How to Contribute  
If you solve the challenge, feel free to fork this repo and submit a PR!  

**Official Preppin' Data Tracker:** [Submit your results](https://preppindata.blogspot.com/).  
