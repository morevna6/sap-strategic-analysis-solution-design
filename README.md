# SAP Strategic Analysis and Solution Design Portfolio

## Overview

This repository contains a collection of hands-on projects completed as part of the **Strategic Analysis and Solution Design SAP** course.

The projects focus on SAP-related business analysis, process modeling, KPI design, dashboard development, risk monitoring, integration performance analysis, and cost-benefit evaluation.

The main goal of this portfolio is to demonstrate how business requirements, process flows, operational data, and strategic objectives can be translated into analytical outputs and decision-support dashboards.

## Project Context

During the course, several SAP business scenarios were analyzed from both a strategic and operational perspective. The work covered areas such as:

- Order-to-cash process analysis
- Order fulfillment monitoring
- SAP integration performance tracking
- API latency analysis
- Vendor and purchase order efficiency
- Project risk monitoring
- Cost-benefit and NPV analysis
- Cash flow trend analysis
- Strategic alignment planning

Some of the course materials included limited sample data. In cases where full datasets were not available, additional data was manually completed or synthetically generated to create realistic analysis scenarios.

## What I Built

This portfolio includes three main types of deliverables:

### 1. Business Process Models

Process models were created to represent SAP-related business workflows and system interactions.

Examples include:

- **Order-to-Cash Process**
  - Order received
  - Purchase order check
  - Order confirmation
  - Premium customer decision
  - Delivery preparation
  - Invoice creation
  - Payment confirmation
  - Order completion or cancellation

- **Order Sync Service**
  - Customer order creation
  - E-commerce database update
  - Sync job trigger
  - Order data transformation
  - Backend API communication
  - API response handling
  - Error logging and retry logic

These models show how business activities, system logic, and decision points connect across departments and platforms.

### 2. KPI Dashboards

Several dashboards were created to monitor operational, financial, and technical performance.

Dashboard examples include:

- **Order Fulfillment Process Dashboard**
  - Order value
  - Order count
  - Order entry automation rate
  - Cycle time
  - Product-level order value
  - Sales organization performance
  - Regional filtering

- **Project Risk Monitoring Dashboard**
  - Total risk count
  - Critical, high, medium, and low risk counts
  - Average risk score
  - Risk category distribution
  - Project-level risk threshold comparison
  - Risk status and mitigation tracking

- **Cost Benefit Dashboard**
  - Total cost by project and year
  - Total benefits by project and year
  - Cash flow
  - Yearly net present value
  - Cumulative NPV
  - Project comparison for investment decision-making

- **API Latency Dashboard**
  - API latency comparison by API name
  - Identification of higher-latency integration points
  - Technical performance monitoring for SAP-related integrations

- **Vendor Efficiency Dashboard**
  - Invoice amount
  - Over-invoice flag
  - Late payment flag
  - Vendor efficiency score

- **US Cash Flow Dashboard**
  - Amount by net due date
  - Accounts receivable trend
  - Late days and accounting document analysis

### 3. Supporting Datasets

The repository also includes supporting CSV and Excel files used to build the dashboards and analysis outputs.

These files include purchase order data, SAP integration performance data, risk monitoring data, generated SAP scenario data, and strategic alignment planning files.

## Repository Structure

```text
SAP-Strategic-Analysis-and-Solution-Design-Portfolio/
│
├── README.md
│
├── dashboards/
│   ├── average-api-latency.pdf
│   ├── cost-benefit-dashboard.pdf
│   ├── order-fulfillment-process-dashboard.pdf
│   ├── project-risk-monitoring-dashboard.pdf
│   ├── us-cash-flow-dashboard.pdf
│   └── vendor-efficiency-dashboard.pdf
│
├── process-models/
│   ├── order-sync-service.pdf
│   └── order-to-cash-process.pdf
│
├── datasets/
│   ├── completed-purchase-orders.csv
│   ├── sap-integration-performance.csv
│   ├── sap-risk-dataset.xlsx
│   ├── sapc4m1sc03.xlsx
│   ├── sapc4m2sc05-generated.csv
│   ├── strategic-alignment-plan.xlsx
│   └── sapc4m4sc05-generated.csv
│
└── notes/
    └── data-disclaimer.md
