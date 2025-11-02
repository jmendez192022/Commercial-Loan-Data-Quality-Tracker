# Loan Data Quality Tracker for Commercial Banking

## Project Summary
This project simulates a commercial banking dataset to enhance data accuracy and governance practices across loan applications and servicing. It identifies missing or mismatched records, implements data quality rules, and produces a logging dataset for improved reporting integrity, aligning vital data with industry compliance standards.

---

## Tools and Skills Used
- **Snowflake**  
- **SQL**  
- **Data Governance**

## Environments Used
- Snowflake Web Interface (Snowsight)  
- Windows / MacOS

---

## Project Walkthrough

1. **Created Database and Schemas**  
   Designed loan applications and loan servicing tables to structure data accurately, ensuring proper relationships and primary keys.

2. **Built SQL Queries**  
   Extracted and joined data to identify missing or mismatched records between tables.

3. **Implemented Data Quality Rules**  
   Created checks to validate critical fields such as CLIENT_ID, LOAN_ID, and other essential data elements.

4. **Generated Logging Dataset**  
   Compiled all findings into a final dataset for reporting, tracking data quality issues over time.

5. **Ensured Compliance Alignment**  
   Verified data integrity to match industry standards and governance requirements, simulating real-world commercial banking data practices.

---

## Visual Overview


### Loan Applications Table Schema
![Loan Applications Table Schema](https://i.imgur.com/KxH5nza.png)


### Loan Servicing Table Schema
![Loan Servicing Table Schema](https://i.imgur.com/1mMSVRM.png)

### Sample Data Quality Check
<p float="left">
  <img src="https://i.imgur.com/maCDqqp.png" width="30%" />
  <img src="https://i.imgur.com/ZFkW5hJ.png" width="60%" />
  <img src="https://i.imgur.com/5LW5fEl.png" width="60%" />
</p>

### Sample Logging Dataset
![Logging Dataset](https://i.imgur.com/BaM7Jrv.png)



---

## Future Improvements
- Expand the project to include additional loan types and risk metrics.  
- Incorporate automated alerting for data quality issues.  
- Build dashboards in Tableau for visualization of loan data quality metrics.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
