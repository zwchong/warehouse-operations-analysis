Warehouse Operations Data Analysis

Overview

This project analyzes operational data from a warehouse to identify bottlenecks and inefficiencies in order fulfillment, picking, inventory control, receiving, and returns management. As an aspiring data analyst, I completed this end-to-end project to demonstrate skills in Excel-based data cleaning, analysis, and dashboard creation.

Objective:

To evaluate warehouse performance using operational data and provide actionable insights to improve efficiency, reduce errors, and optimize labor productivity.

Tools Used
- Microsoft Excel
- Pivot Tables & Charts
- Conditional Formatting
- Basic Formulas & Date Calculations

Dataset Description

The dataset consists of 5 sheets simulating real warehouse operations:

- Order Data - Customer order records including dates, picker assignments, and pick errors
- Picking Log -	Task-level picker performance data
- Inventory Snapshot - Inventory accuracy, stock levels, and movement history
- Receiving & Putaway - Inbound logistics including dock arrival and putaway time
- Error & Returns Log -	Error types, responsibilities, and cost impact

Key Findings

- Order Fulfillment	- Long cycle times; Avg fulfillment: 3.1 days; 35% of orders > 2 days
- Picker Performance -	High error rate;	Picker PCK002 had an 18% error rate (4× avg)
- Inventory Control	- Low accuracy; 26 SKUs > 100% accuracy (Oversupply), 23 SKUs inactive > 90 days
- Inbound Handling -	Putaway delays;	Avg dock-to-stock: 2.53 hrs
- Returns & Errors -	Costly late shipment and damages;	Damages caused $56.80 in avoidable losses

Recommendations

- Fulfillment -	Flag orders >2 days; prioritize high-SKU orders
- Picker Training -	Retrain PCK002; monitor weekly performance
- Inventory Accuracy -	Audit low-accuracy SKUs; remove dead stock
- Inbound Logistics -	Add staffing during peak hours
- Error Prevention -	Trace root cause of damage; investigate late shipments

Dashboard Overview

The Excel file includes a dashboard with:
- Fulfillment Time by Order
- Error Rate by Picker
- Inventory Accuracy Pie Chart
- Dock-to-Stock Time Trend
- Error Type Cost Breakdown
  
Files Included:

warehouse_analysis.xlsx – Full dataset, formulas, pivot tables, and dashboard

Skills Demonstrated:

- Real-world problem framing
- Data cleaning and calculated fields
- Analysis and benchmarking
- Excel dashboard design
- Root-cause analysis and actionable insight generation

Next Steps:

Rebuild analysis in Tableau or Python (pandas)
Add automation features
Perform what-if simulations to estimate savings from recommendations

