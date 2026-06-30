# Cyber Attack Financial Impact Analysis (2021–2025)

## Overview

This project analyzes more than **850 publicly reported cyber incidents** between 2021 and 2025 to investigate their financial consequences and market impact.

The objective was to simulate a real-world business analytics project by designing a relational database, performing analytical SQL queries, and building an interactive Power BI dashboard that communicates the key findings.

---

# Business Problem

Cyberattacks create significant financial and operational risks for organizations. Beyond immediate operational disruption, companies may incur recovery costs, legal expenses, regulatory fines, ransom payments, insurance claims, and substantial changes in investor confidence.

This project aims to answer questions such as:

* Which industries suffer the highest financial losses?
* Does paying a ransom reduce total losses?
* Which sectors recover the slowest after a cyberattack?
* Do larger companies experience greater financial damage?
* Does faster public disclosure influence financial outcomes?

---

# Dataset

The project combines three related datasets linked using **incident_id**.

### 1. Incident Metadata

Contains descriptive information about each cyber incident.

Fields include:

* Company
* Industry
* Country
* Revenue
* Number of employees
* Public / Private status
* Incident dates
* Disclosure dates

---

### 2. Financial Impact

Contains financial information including:

* Direct losses
* Recovery costs
* Legal fees
* Regulatory fines
* Insurance payouts
* Ransom demanded
* Ransom paid
* Total financial loss

---

### 3. Market Reaction

Contains stock market information including:

* Stock price before disclosure
* Stock price after disclosure
* Trading volume
* Market capitalization
* Recovery time
* Industry index

---

# Tools

* SQL
* Power BI
* Git
* GitHub
* Visual Studio Code

---

# SQL Analysis

The SQL analysis is organised into six business sections.

## 1. Industry Financial Risk

Objective:

Identify which industries are most financially exposed to cyberattacks.

Questions answered:

* Highest average financial loss
* Highest total financial loss
* Most frequently attacked sectors
* Above-average sector losses
* Above-average recovery time
* Sector outliers
* Companies exceeding 200% of their sector average

---

## 2. Company Characteristics

Objective:

Understand whether organisational characteristics influence financial losses.

Questions answered:

* Company size vs financial losses
* Public vs private companies

---

## 3. Ransom Analysis

Objective:

Evaluate whether ransom payments influence financial outcomes.

Questions answered:

* Frequency of ransom payments
* Ransom vs total losses
* Above-average ransom sectors
* Industries paying the largest ransoms

---

## 4. Market Reaction

Objective:

Measure investor reaction following cyberattack disclosure.

Questions answered:

* Initial stock price decline
* Thirty-day recovery
* Recovery time
* Slowest recovering industries

---

## 5. Incident Severity

Objective:

Identify the most severe cyber incidents.

Questions answered:

* Incidents above average loss
* Top financial incidents
* Severity classification
* Disclosure speed vs losses

---

## 6. Cost Structure

Objective:

Understand how cyberattack costs are distributed.

Questions answered:

* Direct operational losses
* Recovery costs
* Legal fees
* Regulatory fines
* Insurance payouts
* Insurance coverage

---

# Power BI Dashboard

The dashboard provides an executive summary of the analysis through interactive visualisations.

Pages include:

* Executive Overview
* Industry Financial Risk
* Company Characteristics
* Ransom Analysis
* Market Reaction
* Incident Severity
* Cost Structure
---

# Skills Demonstrated

### SQL

* JOIN
* GROUP BY
* Aggregate Functions
* CASE
* Common Table Expressions (CTEs)
* Subqueries
* Benchmark Analysis
* Data Cleaning
* Business-Oriented Queries

### Power BI

* Data Modelling
* Relationships
* DAX Measures
* Interactive Dashboards
* KPI Cards
* Slicers

---

# Key Business Insights

The dashboard identifies:

* Industries with the greatest financial exposure
* Relationship between ransom payments and losses
* Market reaction following cyberattack disclosure
* Recovery patterns across industries
* Cost composition of cyber incidents
* Company characteristics associated with severe financial impact

---

# Future Improvements

Possible extensions include:

* Time-series forecasting
* Predictive modelling
* Machine Learning classification
* Interactive web dashboard using Python (Dash or Streamlit)
* Automated ETL pipeline

---

# Author

Dominykas Ulevič

Business Management Student | Aspiring Data Analyst

LinkedIn: *(add your profile)*
