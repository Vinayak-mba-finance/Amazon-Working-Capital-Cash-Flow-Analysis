Detailed Description 

This project focuses on building an end-to-end working capital and cash flow analysis for a large-scale e commerce business similar to Amazon, using Microsoft Excel as the primary modeling and visualization tool. The objective is to understand how operational decisions around receivables, inventory, and payables affect liquidity, cash conversion, and ultimately free cash flow.
The starting point of the model is a set of monthly operational assumptions. For each month, the file contains revenue (sales), cost of goods sold (COGS), operating expenses, and capital expenditure (Capex). Based on realistic assumptions for credit sales and credit purchases, the model derives balances for Accounts Receivable (AR), Inventory, and Accounts Payable (AP). These balances are then used to compute Net Working Capital (NWC) as:
Net Working Capital = Accounts Receivable + Inventory − Accounts Payable.
This allows you to track how much cash is tied up in the operating cycle over time.
On top of the working capital calculations, the file includes a cash flow framework that approximates cash collections from customers, cash payments for inventory, ongoing operating expenses, and Capex. From this, the model calculates Cash From Operations and Free Cash Flow (FCF) each month. The evolution of beginning and ending cash balances is also tracked, showing how operational performance impacts the company’s cash position.

The Excel workbook is structured into multiple sheets to maintain transparency and auditability:
•	An Assumptions_Inputs sheet that aggregates the monthly sales, COGS, operating expenses, Capex, and derived working capital metrics.
•	A Working_Capital sheet that highlights AR, Inventory, AP, and Net Working Capital, allowing the analyst to focus specifically on operational efficiency and the cash conversion cycle.
•	A Cash_Flow sheet that lays out cash collections, cash payments to suppliers, operating cash outflows, Capex, and the resulting Free Cash Flow and cash balances.

The centerpiece of the file is the Dashboard sheet. This is designed as an executive-level financial dashboard that visually summarizes the key takeaways:
•	A Net Working Capital trend line across the 12-month period, showing whether the business is freeing up or tying up more capital in operations.
•	A dual-axis chart for Revenue vs Free Cash Flow, making it easy to see whether revenue growth is translating into proportional cash generation or if working capital is absorbing cash.
•	A clustered column chart displaying Accounts Receivable, Inventory, and Accounts Payable by month, providing a visual decomposition of working capital and indicating where optimization opportunities may exist.
•	A KPI panel containing Total Revenue over the period, Average Net Working Capital, and Total Free Cash Flow, giving a quick snapshot of business scale and cash performance.
The dashboard is fully linked to the underlying calculation sheets, ensuring that any change in assumptions (for example, a higher credit sales ratio, changes in operating expenses, or different Capex levels) flows through automatically to the visuals.
From a financial analysis standpoint, the project demonstrates understanding of how working capital management influences cash flow. For instance, by analyzing the NWC trend and the relative size of AR, Inventory, and AP, an analyst can discuss strategies such as tightening credit terms, optimizing inventory turns, or extending supplier payment terms. Linking these movements to Free Cash Flow shows the potential cash benefits of better working capital discipline.
From a technical perspective, the project showcases intermediate-to-advanced Excel skills. It uses structured worksheets, clear labeling, numeric formatting, and multiple chart types arranged thoughtfully on a dashboard page. The design focuses on clarity and executive-readiness: metrics are summarized at the top, trends and composition charts are placed prominently, and the model remains flexible for future enhancement (such as adding scenarios or sensitivity analysis).
Overall, this Amazon Working Capital & Cash Flow Analysis project is a compact but realistic example of how a financial analyst can build a decision-support tool in Excel. It combines operational data, finance theory (working capital and free cash flow), and dashboard design to deliver insights that are directly relevant to corporate finance and FP&A roles.



What’s Inside the Excel – Sheets Overview

1.	Assumptions_Inputs
•	Monthly data for Sales, COGS, Operating Expenses, and Capex.
•	Derived balances for Accounts Receivable, Inventory, and Accounts Payable.
•	Calculated Net Working Capital, Cash From Operations, Free Cash Flow, and Cash Balances.
•	This sheet acts as the core data table feeding the rest of the model.

3.	Working_Capital
•	Focused view of AR, Inventory, AP, and Net Working Capital by month.
•	Lets you analyze trends in working capital components and efficiency.
•	Underpins the Net Working Capital trend chart and the working capital composition chart on the dashboard.

5.	Cash_Flow
•	Lays out monthly cash collections from customers and cash payments for inventory.
•	Includes operating expenses, Capex, Cash From Operations, Free Cash Flow, and beginning/ending cash balances.
•	Supports the Revenue vs Free Cash Flow visual and overall liquidity assessment.

6.	Dashboard
•	Executive-style dashboard with:
•	KPI panel (Total Revenue, Average NWC, Total Free Cash Flow).
•	Net Working Capital trend chart.
•	Revenue vs Free Cash Flow dual-axis chart.
•	AR, Inventory, AP comparison chart.
•	Built for presentation and quick interpretation in interviews or stakeholder meetings.
