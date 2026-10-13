# CSRA - Credit Scoring &amp; Risk Analysis


## **Objective**

This project uses a synthetic loan-application dataset of 20,000 records, to analyse loan size, approval rate, and default history across a simulated lending portfolio. 
________________________________________

## **Tools & Technologies**

1. Python
2. SQL
4. VistudioStudio Code
5. GitHub
________________________________________

### **Project Phases**
**Phase 1: Python Data Pipeline**

The pipeline separates data cleaning, transformation, data quality validation into individual stages and finally ingest into DB for further advanced analysis.
**Pipeline Flow:**

```text
extract_credit_data() 
↓ 
transform_credit_data(df) 
↓ 
validate_credit_data(df) 
↓ 
save_credit_data(df)
```
________________________________________

 **Phase 2: SQL Analysis**
 
SQL queries to execute complex business logic using core relational database mechanics:
1. Top Loan Application category
2. Approval rate per Region
3. Approval rate per Employment Type
4. Average Loan Size by Income Group
