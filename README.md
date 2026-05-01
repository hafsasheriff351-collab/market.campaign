# Marketing Campaign Performance Dashboard

**By: Hafsah I**
**Date of Completion:** March 25, 2025


## Introduction
10,000 Campaigns.<br>
One story worth telling.<br>
Digital marketing spend is growing rapidly, yet businesses continue to allocate budgets across channels such as Search, Email, Social, Display, and Influencer with limited visibility into which actually drives returns. This study analyses 10,000 marketing campaigns run throughout 2025 to evaluate how channel, cost, duration, and audience reach interact to produce revenue and ROI. As organisations shift toward data-driven budget decisions, understanding the true performance drivers behind campaign outcomes becomes a competitive necessity and not just a reporting exercise.
This project analyzes marketing campaign performance using Tableau. The goal is to understand which campaigns, channels, and campaign durations generate the best results in terms of revenue, ROI, conversions, and customer engagement.

## Purpose of Analysis
This project goes beyond dashboards. It asks: what does the data actually mean for a marketing team? Which channels deserve more budget? When does campaign duration start hurting returns? And what separates a campaign that barely breaks even from one that doubles its investment? Marketing teams often spend money across multiple channels without clearly knowing which campaigns are most effective. This analysis combines exploratory data analysis, visual storytelling, and actionable insights — designed not just to inform, but to persuade and guide decisions.

## Dataset
The dataset contains:
- Campaign details (ID, start date, end date, duration)
- Marketing channels (Search, Email, Influencer, etc.)
- Funnel metrics (Impressions, Clicks, Leads, Conversions
- Financial metrics (Cost, Revenue, ROI)
- Created new column → **Campaign Duration**

## 🚀 Top-Line KPIs

| Metric | Value |
|--------|-------|
| 🔥 Total Revenue | $51.0M |
| 💸 Total Spend | $25.5M |
| 📈 Overall ROI | 99.9% |
| 👁️ Total Impressions | 1.52 Billion |
| 🖱️ Total Clicks | 83.4 Million |
| 🎯 Total Conversions | 10.1 Million |
| 📊 Average CTR | 5.48% |
| 🔁 Avg Conversion Rate | 12.12% |

## Tools Used
- Python: For cleaning, EDA, KPI calculation, charts.
- Pandas, NumPy: For grouping, calculations, ROI, CTR, conversion rate, CPC, CPL.
- Matplotlib / Seaborn: For charts analysis
- Tableau: For final interactive dashboard
- GitHub: For portfolio presentation.
- Jupyter Notebook: For showing your full analysis process.

## 🔍 Key Analysis Performed

### 01 · Channel Performance Comparison
Compared all 5 channels across impressions, CTR, conversion rate, cost, and revenue. Identified which channels deliver the best returns per dollar spent using grouped aggregations and bar charts.

### 02 · ROI Distribution Analysis
Examined how ROI is distributed across 10,000 campaigns using histograms and percentile breakdowns. Explored whether high-ROI campaigns cluster around specific channels or durations.

### 03 · Monthly Trend Analysis
Tracked campaign volume, spend, and revenue across all 12 months of 2025 to identify seasonality, peak periods, and budget pacing patterns.

### 04 · Conversion Funnel Analysis
Traced the full funnel — **Impressions → Clicks → Leads → Conversions** — and calculated drop-off rates at each stage per channel to pinpoint where audiences disengage.

### 05 · Campaign Duration vs. ROI
Analysed whether longer campaigns (up to 15 days) outperform shorter ones (5 days) in terms of ROI, conversions, and cost efficiency using scatter plots and correlation tests.

### 06 · Cost Efficiency Benchmarking
Calculated **Cost Per Click (CPC)**, **Cost Per Lead (CPL)**, and **Cost Per Conversion** for each channel to benchmark efficiency and surface the most budget-efficient acquisition paths.

---

## 💡 Key Insights

### 1. Influencer Leads in Reach
Influencer campaigns generated the highest total revenue (**$10.7M**) and the most impressions (**322M**) — making it the top reach channel despite similar spend to others. Best suited for brand awareness at scale.

### 2. Search Converts Best
Search campaigns convert at **12.25%** — the highest conversion rate across all channels. This makes Search the ideal channel for bottom-of-funnel, intent-driven audiences who are closer to purchase.

### 3. Email is the Most Cost-Efficient Channel
Email has the lowest total spend (**$5.06M**) while maintaining the highest CTR (**5.54%**) of any channel. It delivers strong engagement at minimal cost — the clear winner for retention and nurture campaigns.

### 4. 60% of Leads Are Never Converted
With **25M leads** captured but only **10M conversions**, 60% of the pipeline is lost between lead capture and final conversion. This represents the single largest untapped revenue opportunity in the dataset.

### 5. April & May Are Peak Campaign Months
April (**865 campaigns**) and May (**864 campaigns**) are the most active months. February (**759**) and September (**778**) are the quietest — useful for seasonal planning and budget allocation decisions.

### 6. ROI Is Uniformly Distributed (0.0 – 2.0)
Every campaign delivers an ROI between 0 and 2, perfectly evenly spread — with an average of **1.00**. In real-world data, this would show skew and outliers worth investigating. For this dataset, it signals a strong baseline across all channels.

## Dashboard Features
- KPI cards for total revenue, total cost, conversions, and ROI
- Channel performance comparison
- Funnel visualization
- Campaign duration analysis
- Profitability and efficiency insights

## Business Recommendations
### 🟢 High Priority — Scale Search for Performance Campaigns
With the highest conversion rate (12.25%) and strong revenue, **Search should receive a larger share of performance marketing budgets** — especially for campaigns targeting users with clear purchase intent.

### 🔵 High Priority — Use Email as a Low-Cost Retention Engine
Email's lowest cost per campaign and highest CTR make it the best channel to re-engage existing customers and warm leads without burning performance budget. **Scale Email for nurture sequences and CRM campaigns.**

### 🟣 Medium Priority — Position Influencer as Awareness, Not Conversion
Influencer drives the highest impressions and revenue overall, but has the lowest conversion rate (12.00%). **Position Influencer campaigns as top-of-funnel awareness plays**, not direct conversion drivers — then retarget those audiences via Search or Email.

### 🟡 Medium Priority — Invest in Lead Nurturing to Close the 60% Gap
With 60% of captured leads never converting, **investing in better CRM workflows, retargeting, and follow-up sequences** could unlock significant revenue from existing pipeline without increasing acquisition spend.

### 🔴 Strategic — Front-Load Budget in April & May
Campaign volume peaks in April and May — **align media spend and campaign launches with these high-activity windows**. Use quieter months (Feb, Sep) for planning, creative production, and A/B test setup rather than heavy spend.

## Data Processing & EDA (Python)
- Performed data cleaning and transformation using Python.
- Calculated key performance metrics such as CTR, Conversion Rate, CPC, CPL, and Profit.
- Conducted exploratory data analysis to identify trends, correlations, and patterns before building dashboards in Tableau.

## Project Files
- `data/` contains the dataset
- `dashboard/` contains the Tableau workbook
