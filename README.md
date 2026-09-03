📊 Project Overview

This project analyzes campaign-level marketing data spanning Jan–Dec 2023 across 5 companies, 6 channels, and 10 U.S. locations, using Python for data cleaning, exploratory analysis, and visualization.

Dataset: marketing_campaign.csv

🛠️ Tools & Libraries
Python (Pandas, NumPy)
Matplotlib, Seaborn
Google Colab
🔍 Analysis Structure
Data Cleaning — datetime conversion, cost parsing, duration extraction
Campaign & Channel Performance — ROI by company, conversion by channel, cost-ROI correlation
Time-Based Analysis — duration distribution, conversion rate trends, engagement score trends
Geographic Analysis — acquisition cost by location, location × audience conversion, ROI distribution
📈 Key Findings
Area	Finding
Top company (ROI)	Alpha Innovations — 187.8% avg ROI
Top channel (conversion)	Facebook — 4.78% avg conversion rate
Cost vs. ROI	Moderate negative correlation (r = −0.57) — higher spend ≠ better ROI
Dominant campaign duration	30 days (9,960 of 22,029 campaigns)
Conversion rate trend	Flat across the year (~4.7–4.8%)
Engagement score trend	Strong upward trend — 5.05 (Jan) → 8.50 (Dec), ~70% increase
Highest acquisition cost	New York ($5,650.63)
Best location + audience combo	San Francisco, Men 18–24 — 4.85% conversion
Top ROI location	Chicago — 10.7% of total ROI
💡 Recommendations
Control acquisition cost rather than reallocating between companies/channels — variance there is narrow, but cost has the strongest relationship with ROI.
Standardize campaigns around a 30-day duration, the dominant and best-tested format.
Investigate the H2 2023 engagement surge to identify replicable drivers for future campaigns.
Prioritize Men 18–24 and All-Ages segments in San Francisco, Dallas, and Los Angeles — the strongest-converting location-audience pairs.
📁 Repository Contents
├── marketing_campaign_analysis.ipynb   # Full EDA notebook
├── Marketing_Campaign_Summary_Report.docx  # One-page findings summary
└── README.md
