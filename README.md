# Branch, Project & Employee Profitability Analysis

An Excel-based financial analysis and reporting system developed to analyse profitability across projects, employees/resources and branches, while supporting management decision-making and pre-payment profitability checks.

> [!IMPORTANT]
> **Data Disclaimer**
>
> This project uses **100% synthetic data** created exclusively for demonstration and portfolio purposes.
>
> The data does not represent actual company records or financial results. Only the general **reporting structure, field headings and format** are representative of the type of information encountered in my work experience.
>
> No confidential employee, customer, project, financial or other proprietary information has been used in this project. Names, IDs, values and other data points have been created or modified for demonstration purposes.
## Company Profile

**EngiStaff Solution Private Limited** is an engineering services company providing engineering expertise and technical resources to clients across India.

The company supports clients through engineering consultancy, design capabilities and specialised technical manpower with domain expertise. Its operations span specialised sectors including automation and mobility, aerospace and defence, renewable energy and utilities.

The company operates through multiple branches and provides engineering resources to clients under different projects and assignments.

---

## Background

This project was developed based on my experience working as a **Finance & Accounts Executive** in an engineering services organisation.

The objective was to build a structured reporting process that could help management and finance stakeholders understand profitability at different levels and support financial decision-making.

The underlying information was maintained across multiple Excel-based datasets. Analysing profitability for individual projects, employees and branches required repeated consolidation, filtering and manual analysis.

The project was developed to convert this information into a consolidated and reusable profitability reporting framework.

---

## Objectives

The main objectives of the project were to:

- Analyse project-wise and customer-wise profitability
- Analyse employee/resource-wise profitability
- Compare profitability across branches
- Identify profitable and loss-making projects
- Identify low-profitability and loss-making resources
- Highlight projects with unusual income and expense patterns
- Identify areas that may require further billing or financial investigation
- Calculate operating profitability after allocated overhead
- Support pre-payment profitability checks
- Provide management with a consolidated view of financial performance

---
## Approach

The reporting process follows the structure:

**Source Data → Data Consolidation → Classification & Grouping → Profitability Calculations → Reports & Dashboard**

The available Excel datasets were consolidated and transformed using **Power Query** to create a structured underlying dataset. **Advanced Excel formulas and Power Pivot** were then used for calculations, data modelling and profitability analysis. The processed data was subsequently used to build interactive reports with filters and selection controls for project, employee and branch-level analysis.

The resulting model feeds the detailed profitability reports and executive dashboard, providing a consistent reporting structure across the different levels of analysis.

---
## Reporting Structure

The final workbook consists of five major reporting components.

### 1. Executive Dashboard

<img width="1600" height="950" alt="Dashboard" src="https://github.com/user-attachments/assets/93a8bd52-a6d8-448c-adfb-a259d1c6dede" />

An interactive dashboard providing a management-level summary of overall financial performance.

The dashboard acts as the starting point for management review, with detailed reports providing further analysis.

---
### 2. Branch-wise Report
<img width="1600" height="950" alt="Branch wise p l report" src="https://github.com/user-attachments/assets/2ac68fa5-ae89-49a0-a6ce-d7fa28d6b800" />

The Branch-wise Report provides a comparative view of financial performance across branches.

This allows management to compare branch performance and identify branches requiring further investigation.

---
### 3. Project & Customer-wise Report
<img width="1600" height="950" alt="Project wise p l report" src="https://github.com/user-attachments/assets/4acbcece-38e8-44d3-8468-4de3787044d4" />

The report highlights both profitable and loss-making projects.

It also contains an **Unbilled Projects** section to identify projects where expenses have been recorded without corresponding income/billing in the analysed data.

These exceptions can then be investigated against project status, contractual billing terms, invoices raised and recoverable expenses.
One of the useful aspects of the project-wise analysis is that it can help highlight areas that may require further investigation.

Project expenses and income are analysed together at the project level. This makes it easier to notice unusual situations, such as a project showing relatively high expenses with little or no corresponding income in the available data.

These situations do not necessarily indicate billing errors, revenue leakage or any other specific issue. There may be valid operational or contractual reasons for the difference.

However, the report acts as an **analytical indicator**, directing attention towards projects where the financial pattern appears unusual.

For example:

> **High project expenses + low/no recorded income → "This project may need to be checked."**

The identified projects can then be reviewed against project status, billing arrangements, invoices raised, expense nature and other relevant information.

The purpose is to make potential areas of concern easier to notice and reduce the effort required to identify where further analysis may be needed.

---
### 4. Employee-wise Profitability Report
<img width="1600" height="953" alt="Employee wise P L report" src="https://github.com/user-attachments/assets/dcec7eec-40aa-4462-91af-0eecdfc65269" />

Engineering resources are a major component of the business model, making employee/resource-level profitability an important analytical area.

The Employee-wise Report provides:

**Income → Expense → Profit → Profit Margin → Allocated Overhead → Operating Profit**

This enables management to identify resources generating healthy margins as well as resources operating at low or negative profitability.

---
### 5. Individual Resource P/L Report
<img width="1600" height="950" alt="Individual resourse P L report" src="https://github.com/user-attachments/assets/ec767e5f-503e-43d5-b534-9764a40b8ce8" />

The Individual Resource P/L Report was developed specifically as a **pre-payment profitability check**.

When processing payments for multiple employees/resources, reviewing individual profitability through the underlying dataset can require repeated filtering and pivoting.

The report simplifies this process.

The user can:

1. Enter or paste the required Employee IDs.
2. Select the relevant month.
3. Obtain the corresponding P&L for the selected employees.

The report calculates:

**Profit = Income − Expense**

and:

**Operating Profit = Profit − Allocated Overhead**

An overhead rate is allocated by the corporation and applied to calculate the operating profitability of each employee.
This provides a quick profitability review before payment disbursement.

---
## Tools & Technologies utilised

- **Microsoft Excel** – Reporting, calculations and interactive analysis
- **Power Query** – Data consolidation and transformation
- **Power Pivot** – Data modelling and analysis
- **Advanced Excel Formulas** – Calculations, lookups, conditional logic and dynamic reporting
  
---
## Project Outcome

The final workbook converts multiple Excel-based financial and operational datasets into a structured profitability reporting framework.

The model provides a consistent approach to analysing:

- Overall financial performance
- Branch profitability
- Project and customer profitability
- Employee/resource profitability
- Individual resource P&L
- Unusual income and expense patterns

The project combines **financial reporting, profitability analysis, exception analysis and payment review** into a single Excel-based reporting system.

The primary objective was not simply to present financial data, but to make the data easier to analyse and to direct attention towards areas where further investigation or management action may be required.
