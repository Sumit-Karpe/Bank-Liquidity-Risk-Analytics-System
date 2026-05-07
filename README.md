# Bank Liquidity Risk Analytics System

![Banner](https://github.com/Sumit-Karpe/Bank-Liquidity-Risk-Analytics-System/blob/main/images/Bank_of_America_logo.svg.png)

## Overview

This project simulates an enterprise-grade liquidity risk monitoring system used by global banking institutions to track treasury liquidity, funding exposure, operational settlement performance, and regulatory liquidity compliance.

The solution combines:

* **Alteryx** for automated ETL and liquidity data processing
* **Tableau** for interactive risk analytics dashboards
* **Synthetic treasury datasets** generated using AI-assisted workflows
* Statistical monitoring techniques for liquidity stress detection

The project was designed to replicate real-world treasury analytics and liquidity surveillance workflows commonly used in financial institutions.

---

# Executive Summary

Financial institutions must continuously monitor liquidity health to maintain regulatory compliance and avoid funding stress.

This project builds an end-to-end analytics pipeline capable of:

* Monitoring daily liquidity movements
* Detecting abnormal outflows
* Tracking FX funding concentration risk
* Measuring operational settlement failures
* Identifying liquidity stress events using statistical techniques

The system transforms raw treasury datasets into structured analytical outputs that support executive decision-making and operational risk monitoring.

---

# Business Problem

Liquidity risk management is one of the most critical functions within banking operations.

Treasury teams require systems capable of:

* Monitoring cash inflows and outflows in near real-time
* Measuring Liquidity Coverage Ratio (LCR) stability
* Detecting operational settlement bottlenecks
* Identifying short-term rollover exposure in FX funding markets
* Providing early warning indicators for liquidity stress events

Traditional manual reporting processes are slow, fragmented, and operationally expensive.

This project demonstrates how an automated analytics pipeline can improve liquidity surveillance and operational visibility.

---

# System Architecture

```text
Raw Treasury Data
       ↓
Alteryx ETL Pipeline
       ↓
Liquidity Risk Datasets
       ↓
Tableau Interactive Dashboards
       ↓
Executive Risk Monitoring
```

---

# Dashboard Modules

## 1. Regulatory Liquidity Overview

Tracks:

* Liquidity Coverage Ratio (LCR)
* Net liquidity flow trends
* Liquidity compression periods
* Regulatory liquidity buffer stability

This dashboard helps identify abnormal net outflow periods and sustained liquidity stress. 

---

## 2. Business Unit Liquidity Contribution

Analyzes:

* Business-unit-level liquidity flows
* Rolling 7-day net flow trends
* Structural funding pressure
* Liquidity volatility contribution

The dashboard identifies which divisions contribute most to liquidity instability. 

---

## 3. FX Funding & Exposure Risk

Monitors:

* FX swap notional exposure
* Funding rollover concentration
* Maturity ladder distribution
* Basis spread dynamics

This module evaluates short-term funding risk and currency exposure concentrations. 

---

## 4. Settlement & Operational Risk

Tracks:

* Settlement workflow drop-offs
* Operational failure rates
* Settlement delays
* Liquidity timing risks

Operational inefficiencies can significantly impact liquidity timing and funding stability. 

---

## 5. Volatility & Stress Detection

Implements:

* Liquidity volatility analysis
* Z-score anomaly detection
* Statistical stress event monitoring
* Currency-level balance volatility

This module provides early warning indicators for abnormal liquidity events. 

---

# Alteryx ETL Workflow

The Alteryx workflow automates treasury data transformation and liquidity analytics generation.

Key workflow capabilities include:

* Data cleansing and standardization
* Signed liquidity flow calculation
* Daily net flow aggregation
* Rolling 7-day liquidity averages
* Liquidity stress flag generation
* FX basis spread calculations
* Maturity bucket classification

The workflow generates two analytical outputs:

1. Liquidity Monitoring Dataset
2. FX Funding Risk Dataset

Detailed workflow explanation available here:

`alteryx/documentation/alteryx_workflow_documentation.pdf`



---

# Datasets

| Dataset                 | Purpose                          |
| ----------------------- | -------------------------------- |
| Cash Transactions       | Treasury inflow/outflow tracking |
| Settlement Workflow Log | Operational settlement analysis  |
| Daily Cash Balances     | Liquidity trend monitoring       |
| Liquidity Buffer        | Regulatory liquidity metrics     |
| FX Swap Positions       | Funding exposure analysis        |

---

# Technology Stack

| Category                       | Tools                     |
| ------------------------------ | ------------------------- |
| ETL & Data Processing          | Alteryx                   |
| Visualization                  | Tableau                   |
| Data Storage                   | CSV / Excel               |
| Statistical Analysis           | Tableau Calculated Fields |
| AI-Assisted Dataset Generation | ChatGPT / Perplexity      |

---

# Dashboard Preview

## Regulatory Liquidity Overview

![Liquidity Overview](assets/dashboard-previews/liquidity-overview.png)

---

## FX Funding & Exposure Risk

![FX Risk](assets/dashboard-previews/fx-risk-analysis.png)

---

# Key Analytics Features

* Automated liquidity monitoring
* Rolling liquidity trend calculations
* Stress day detection
* Funding concentration analysis
* Cross-dashboard filtering
* Interactive treasury analytics
* Liquidity volatility monitoring

---

# Project Outcomes

This project demonstrates:

* Enterprise BI dashboard development
* ETL workflow engineering
* Treasury analytics implementation
* Liquidity risk monitoring concepts
* Operational risk analytics
* Financial data storytelling
* Interactive dashboard design

---

# AI Usage Disclosure

All datasets used in this project were synthetically generated using AI-assisted workflows for educational and portfolio purposes.

No real banking customer information or confidential financial data was used.

The generated datasets are fully GDPR compliant.

---

# Repository Structure

```text
assets/      → dashboard previews & architecture diagrams
data/        → raw and processed datasets
alteryx/     → ETL workflows
tableau/     → Tableau dashboards
docs/        → technical documentation
```

---

# Future Improvements

* Real-time streaming ingestion
* Python-based anomaly detection
* Snowflake data warehouse integration
* Automated alerting pipeline
* Risk scoring models
* Cloud deployment architecture

---

# Author

## Sumit Karpe

Aspiring Data Analyst / BI Engineer focused on:

* Tableau
* Alteryx
* Data Engineering
* Business Intelligence
* Financial Analytics

LinkedIn: https://www.linkedin.com/in/sumit-karpe-252978336/

---
