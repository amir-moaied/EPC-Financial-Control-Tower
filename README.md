# EPC Financial Control Tower | Power BI Dashboard for EPC Project Financial Management

**An integrated Power BI portfolio case study for project financial control, document-level exposure monitoring, receivables and payables analysis, collection performance, and cash flow forecasting in Engineering, Procurement, and Construction (EPC) projects.**

This project demonstrates how **Microsoft Power BI, DAX, Power Query, and data modeling** can bring key EPC project finance indicators into a unified management reporting and decision-support environment.

> **Portfolio demonstration:** All records, counterparties, document references, workflow statuses, transaction amounts, and forecast figures in this repository are synthetic and illustrative. They do not represent actual employer, client, supplier, or project financial information.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Dashboard Modules](#dashboard-modules)
- [Selected Demonstration KPIs](#selected-demonstration-kpis)
- [Technical Stack](#technical-stack)
- [Key Analytical Capabilities](#key-analytical-capabilities)
- [Project Report and Dashboard PDFs](#project-report-and-dashboard-pdfs)
- [Data Transparency and Confidentiality](#data-transparency-and-confidentiality)
- [About the Author](#about-the-author)

---

## Project Overview

Financial control in EPC projects requires coordinated visibility across financial documents, employer receivables, supplier payables, settlement activity, approval workflows, overdue exposure, and expected future cash movements.

The **EPC Financial Control Tower** is a Power BI dashboard portfolio designed to organize these related areas into five connected analytical views. It supports executive-level monitoring, document-level review, aging analysis, counterparty prioritization, and forward-looking cash flow assessment.

The report snapshot is dated **29 October 2026**. All displayed values are illustrative demonstration data.

## Dashboard Modules

The repository contains five Power BI dashboard modules. Each module has an individual PDF preview, and the complete five-page report is also available below.

### 1. Executive Control Tower

An executive overview of EPC project financial performance and risk, bringing together actual cash flow, open receivables and payables, overdue exposure, high-risk balances, and approval SLA exceptions.

**Key views include:**

- Monthly actual receipts and payments
- Net actual cash flow
- Open receivables and open payables
- Total overdue and high-risk financial exposure
- Approval SLA breach value
- Outstanding exposure by Engineering, Procurement, and Construction work packages

[View Executive Control Tower (PDF)](Screenshots/Executive_Control_Tower.pdf)

### 2. Document-Level Financial Exposure & Control

A document-level financial control view for monitoring invoice values, outstanding balances, overdue amounts, risk categories, and workflow status.

**Key views include:**

- Open receivables and open payables
- Total overdue exposure
- Approval SLA breach count
- Outstanding exposure by High, Medium, and Low risk levels
- Document workflow status distribution
- Financial document register with due date, invoice value, open balance, days overdue, risk level, and workflow status

[View Document-Level Financial Control (PDF)](Screenshots/Document_Level_Financial_Control.pdf)

### 3. Aging & Collection Analysis

An aging analysis of employer receivables and supplier payables, designed to highlight overdue concentration and long-outstanding financial obligations.

**Key views include:**

- Receivables aging profile
- Payables aging profile
- Not-due, 1–30, 31–60, 61–90, and 91+ day aging buckets
- Receivables and payables overdue percentages
- 91+ day overdue balances

[View Aging & Collection Analysis (PDF)](Screenshots/Aging_Collection_Analysis.pdf)

### 4. Collection & Payment Performance

A counterparty-focused view of employer collection performance and supplier payment exposure, helping prioritize follow-up on overdue receivables and payables.

**Key views include:**

- Collection coverage
- Supplier payment coverage
- Number of overdue receivable and payable documents
- Top 10 overdue employer receivables
- Top 10 suppliers by overdue payables
- Counterparty exposure, days past due, and weighted average overdue days

[View Collection & Payment Performance (PDF)](Screenshots/Collection_Payment_Performance.pdf)

### 5. Cash Flow Forecast & Early Warning

A forward-looking EPC project cash flow monitoring view combining weighted expected inflows and outflows, cumulative net forecast movement, and financial exception queues.

**Key views include:**

- Daily weighted forecast inflows
- Daily weighted forecast outflows
- Cumulative net weighted forecast cash flow
- 30-day and 60-day forecast indicators
- Approval SLA exceptions based on the configured 10-day threshold
- High-risk open financial exposure requiring priority review

**Forecast interpretation:** Cumulative net weighted forecast cash flow represents accumulated forecast movement over the selected horizon. It is not the actual bank cash balance.

[View Cash Flow Forecast & Early Warning (PDF)](Screenshots/Cash_Flow_Forecast_Early_Warning.pdf)

---

## Selected Demonstration KPIs

The following values are taken from the illustrative report snapshot dated **29 October 2026**. They are included to show the types of financial indicators presented by the dashboards, not to report actual project results.

| KPI | Demonstration value |
|---|---:|
| Net actual cash flow | €0.93M |
| Open receivables | €4.20M |
| Open payables | €2.30M |
| Total overdue exposure | €5.27M |
| High-risk open exposure | €3.49M |
| Net weighted forecast cash flow – 30 days | €0.61M |
| Net weighted forecast cash flow – 60 days | €0.93M |

---

## Technical Stack

| Technology | Role in the project |
|---|---|
| Microsoft Power BI | Interactive financial dashboards and management reporting |
| DAX | Financial KPIs, calculations, and analytical measures |
| Power Query | Data preparation and transformation |
| Data Modeling | Structured analytical context for financial reporting |
| Microsoft Excel | Source data preparation |

## Key Analytical Capabilities

- EPC project financial performance monitoring
- Document-level financial exposure and outstanding balance analysis
- Employer receivables and supplier payables aging
- Collection coverage and supplier payment coverage analysis
- Weighted cash flow forecasting and cumulative forecast movement
- Financial risk classification and high-risk exposure monitoring
- Approval SLA exception monitoring
- Counterparty prioritization and Top 10 exposure analysis
- Interactive filtering and drill-through reporting
- Executive-oriented project financial reporting

## Project Report and Dashboard PDFs

**Complete report:**

[Download the Complete EPC Financial Control Tower Report (PDF)](https://raw.githubusercontent.com/amir-moaied/EPC-Financial-Control-Tower/main/Portfolio/EPC_Financial_Control_Tower_Report.pdf)

**Individual dashboard PDFs:** The five links in the [Dashboard Modules](#dashboard-modules) section open the corresponding one-page dashboard reports in the `Screenshots` folder.

---

## Data Transparency and Confidentiality

This is an independent portfolio demonstration developed with synthetic sample data. Financial records, invoice references, counterparties, amounts, workflow statuses, and forecast events are illustrative.

No confidential employer, client, supplier, or live project information is intentionally included. All financial values should be interpreted as demonstration figures, not actual EPC project results.

## About the Author

**Amir Moaied**  
Senior Project Cost Control Engineer | Power BI & Financial Analysis

Professional focus:

- EPC Project Financial Management
- Project Cost Control
- Business Intelligence and Power BI
- DAX and Power Query
- Financial Reporting Automation
- Cash Flow Analysis and Forecasting
- Management Reporting and Data Visualization

**LinkedIn:** [Amir Moaied](https://www.linkedin.com/in/moaied-amir/)

---

*Developed as a professional Power BI portfolio case study focused on EPC project financial control and business intelligence.*
