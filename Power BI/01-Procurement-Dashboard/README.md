# Procurement Analytics Dashboard

This project uses Power BI to analyze procurement data from a simulated SAP S/4HANA procurement workflow.

The dashboard transforms purchase order, goods receipt, invoice, and three-way match data into an interactive procurement analytics dashboard.

## Project Objective

The goal of this project was to build a procurement dashboard that can:

- Monitor total procurement spend
- Track purchase order volume
- Analyze supplier and material spending
- Identify three-way match exceptions
- Measure exception rates
- Analyze quantity variances
- Filter procurement activity by vendor and material
- Present procurement findings through an interactive Power BI dashboard

## Tools Used

- Power BI Desktop
- DAX
- Microsoft Excel
- SAP S/4HANA procurement concepts

## Dashboard KPIs

- **Total Procurement Spend:** $3,455
- **Total Purchase Orders:** 3
- **Exception Rate:** 66.67%

## Dashboard Analysis

### Spend by Vendor

Vendor VEN-002 represents the largest share of procurement spend, driven primarily by PO-45003.

### Spend by Material

Material MAT-1003 represents the largest material spend at $2,175.

### Spend by Category

The Components category represents the largest category spend.

### Three-Way Match Analysis

The dashboard identifies two transactions with an overall status of **Exception / Hold** and one approved transaction.

This produces an overall exception rate of **66.67%**.

### Quantity Variance

PO-45003 has a quantity variance of **7 units**.

The purchase order requested 150 units, while 145 were received and 143 were accepted. However, 150 units were invoiced, creating a three-way match exception.

## Key Procurement Finding

The primary control issue identified in the simulation is PO-45003.

The transaction contains a quantity discrepancy between the ordered, received, accepted, and invoiced quantities. The resulting exception demonstrates how three-way matching can identify transactions that should be reviewed before payment.

## Interactive Features

The dashboard includes slicers for:

- Vendor ID
- Material Number

Selecting a vendor or material dynamically updates the dashboard's KPIs and visualizations.

## Dashboard Components

- Total Procurement Spend KPI
- Total Purchase Orders KPI
- Exception Rate KPI
- Spend by Vendor
- Spend by Material
- Match Status Breakdown
- Quantity Variance by PO
- Spend by Category
- Vendor ID slicer
- Material Number slicer

## Portfolio Context

This project is part of my procurement and supply chain analytics portfolio.

The portfolio progression includes:

1. Excel Procurement Analysis
2. SAP Procurement Simulation
3. Power BI Procurement Dashboard
4. SQL Supply Chain Analysis
5. Supply Chain Analytics Projects
