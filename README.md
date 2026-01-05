Bank Campaign Analytics Project
Executive Summary
This repository presents an end-to-end analytics project focused on understanding customer subscription behavior in a bank marketing campaign. The objective is to translate raw customer data into actionable business insights using Python for analysis and Power BI for visualization and KPI reporting. The project follows industry-standard analytics practices and is structured to be easily reviewed by recruiters and stakeholders.

Business Objective
Financial institutions often face low conversion rates in term deposit campaigns due to broad targeting and inefficient follow-ups. This project aims to:

Identify key customer and campaign attributes influencing subscription outcomes
Measure campaign effectiveness using well-defined KPIs
Provide data-driven recommendations to improve conversion rates and operational efficiency
Dataset Overview
Dataset: Bank Marketing Dataset
Format: CSV
Size: ~45,000 records
Key Attributes: Customer demographics, loan status, contact duration, campaign frequency, subscription outcome
Tools & Technologies
Programming & Analysis: Python (Pandas, NumPy)
Visualization: Matplotlib, Seaborn
BI & Reporting: Power BI (DAX, KPI Cards, Trend Analysis)
Version Control: Git & GitHub
Methodology
Data ingestion and validation
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
KPI definition and calculation
Visualization and dashboard development in Power BI
Insight generation and business recommendations
Key Performance Indicators (KPIs)
Subscription Conversion Rate (%)
Loan Holders Ratio (%)
Campaign Success Rate
Average Contact Duration
Monthly Subscription Trend
Key Insights
Customers without existing personal loans demonstrated a higher likelihood of subscription.
Longer contact durations were strongly associated with successful conversions.
Campaign effectiveness varied significantly by month, indicating seasonality effects.
Excessive follow-up attempts negatively impacted conversion probability.
Business Recommendations
Prioritize outreach to customers without existing loan obligations.
Optimize campaign strategies to balance contact frequency and customer engagement.
Allocate marketing resources toward high-performing months.
Use contact duration as a quality indicator rather than increasing call volume.
Power BI Dashboard
The Power BI dashboard provides:

Executive-level KPI cards for quick performance assessment
Monthly trend analysis of subscription behavior
Customer segmentation by loan status and demographics
Comparative visuals to support decision-making
Dashboard screenshots are included in the /images directory for quick review.

Repository Structure
Bank-Marketing-Analytics/
│── data/           # Raw and cleaned datasets
│── notebooks/      # Jupyter notebooks for analysis
│── powerbi/        # Power BI dashboard files
│── images/         # Dashboard screenshots
│── README.md
How to Reproduce the Analysis
Clone the repository
Open the Jupyter notebook in notebooks/
Install required Python dependencies
Execute cells sequentially to reproduce results
Open the Power BI file to explore the dashboard
Commit Message Guidelines
This repository follows clear and professional commit conventions:

Format:

<type>: <concise description>
Commit Types:

init – Initial project setup
data – Dataset additions or updates
analysis – EDA and analytical logic
viz – Visualizations or dashboard updates
kpi – KPI or DAX-related changes
docs – Documentation updates
fix – Bug fixes or corrections
Examples:

init: establish project structure
data: add cleaned bank marketing dataset
analysis: evaluate subscription trends by month
viz: add loan holder ratio visualization
kpi: implement subscription conversion DAX
docs: enhance README with insights
Common Version Control Challenges & Best Practices
Large files: Use Git LFS or include dashboard screenshots instead of large binaries
Unclear history: Commit small, logically grouped changes
Poor documentation: Keep README updated alongside code changes
Disorganized structure: Maintain a clear and consistent folder hierarchy
Final Review Checklist
README clearly explains business context and outcomes
Code and notebooks execute without errors
Power BI dashboard screenshots included
Commit history is clean and descriptive
Professional Note
This repository is designed as a portfolio project suitable for Data Analyst, Business Analyst, and Power BI Developer roles. It is recommended to pin this rep
