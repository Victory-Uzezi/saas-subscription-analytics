# SaaS Subscription Analytics Platform

**Research Focus:** Human-Centered Dashboard Design & Multi-Stakeholder Information Architecture

## Abstract
Investigation of optimal visualization strategies for complex subscription analytics across diverse stakeholder groups. This project develops a comprehensive SaaS analytics platform to explore how interactive dashboard design can optimize decision-making efficiency while addressing the "curse of dimensionality" in executive reporting.

## Research Questions
- How can parameter-driven interfaces enable role-based data exploration without cognitive overload?
- What KPI visualization strategies best support different stakeholder decision-making processes?
- How do cohort analysis methodologies translate to interactive business intelligence systems?

## Technical Implementation

### Dataset Generation
- **Tool:** Python
- **Scale:** 10,000+ realistic customer records (2021-2024)
- **Structure:** Four normalized tables (Customers, Subscription Events, Monthly Snapshots, Acquisition Costs)
- **Features:** Customer lifecycles, churn modeling, acquisition channel tracking

### Analytics Framework
**Core Metrics:**
- Revenue: MRR, ARR, Net New MRR decomposition
- Customer: Retention rates, churn analysis, trial conversion
- Efficiency: CAC, LTV, LTV:CAC ratios

**Advanced Analysis:**
- Cohort retention heatmaps
- Conversion funnel optimization
- Revenue waterfall analysis

### Interactive Dashboard Features
- Multi-dimensional filtering (time, channel, plan type)
- Parameter switches for metric/customer views
- Role-based information architecture
- Real-time KPI calculations

## Key Findings
- Revenue Growth: Net New MRR remained positive overall, with upgrades and new signups outweighing churn.
- Retention: Cohort analysis showed most churn occurred in the first 3 months, while long-term customers drove higher LTV.
- Trial Conversion: ~25% of trials converted to paid, with referrals and organic channels performing best.
- Plans: Pro & Premium plans contributed the majority of revenue, while Basic had the highest churn.
- Acquisition Efficiency: CAC was lowest for referrals/organic, highest for paid ads; only some channels achieved strong LTV:CAC ratios.

## Technical Skills Demonstrated
- **Data Engineering:** Python data generation, SQL modeling, ETL pipeline design
- **Analytics:** Cohort analysis, funnel optimization, KPI development
- **Visualization:** Interactive parameter systems, multi-stakeholder dashboard design
- **Business Intelligence:** Subscription metrics expertise, stakeholder requirement analysis

## Research Applications
This work directly supports research in:
- **Explainable AI:** Interpretable business metric calculation
- **Human-Centered Data Science:** Multi-stakeholder interface design
- **Automated Dashboard Generation:** Parameter-driven visualization systems

## Files Structure
├── data/
│   ├── customers.csv
│   ├── subscription_events.csv
│   └── monthly_snapshots.csv
├── notebooks/
│   ├── data_generation.ipynb
│   └── exploratory_analysis.ipynb
├── docs/
│   └── technical_methodology.pdf
└── images/
├── dashboard_overview.png
└── cohort_analysis.png

## Live Dashboard
https://public.tableau.com/app/profile/victory4333/viz/FlowsyncSaasDashboard/FlowSyncCustomerOverview

---
**Author:** Victory Omovrah  
**Contact:** victoryomovrah12@gmail.com  
**Portfolio:** https://public.tableau.com/app/profile/victory4333/vizzes
