# 📊 Y Combinator Success Analytics Dashboard

## Dashboard Preview
<img width="909" height="511" alt="home page" src="https://github.com/user-attachments/assets/10405cd2-32e3-423f-83b1-2a5514fd279c" /><img width="906" height="508" alt="market" src="https://github.com/user-attachments/assets/a84522e1-1abe-45eb-b789-db20c879e29c" />

<img width="887" height="496" alt="success insights" src="https://github.com/user-attachments/assets/4ec7ea05-b5ad-4111-a8fd-941ea4637844" />

## 🚀 Project Overview
This project provides a comprehensive analysis of **Y Combinator's startup ecosystem**, examining **5,407 companies across 20 years (2005–2025)** to identify success patterns, industry trends, and key performance indicators.  
Through **interactive Power BI dashboards**, the analysis reveals critical insights about startup success rates, industry performance, and the evolution of the world’s most successful startup accelerator program.

---

## 🎯 Objectives

### Primary Goals
- Analyze startup success patterns across Y Combinator’s entire portfolio  
- Identify high-performing industries and optimal company characteristics  
- Track YC program evolution and its impact on success rates over time  
- Provide data-driven insights for entrepreneurs, investors, and program managers  
- Create interactive visualizations for stakeholder decision-making support  

### Success Metrics
- ✅ Comprehensive analysis of **5,407+ company records**  
- ✅ Multi-dimensional dashboard with **15+ interactive visualizations**  
- ✅ **98.5%** data completeness and accuracy achieved  
- ✅ Actionable insights for multiple stakeholder groups  

---

## 📂 Data Description and ERD
<img width="607" height="519" alt="BRD" src="https://github.com/user-attachments/assets/76590929-b06e-4e21-b223-5ea073d66832" />

**Dataset Overview**
- Source: YC Company Database  
- Size: 5,407 companies  
- Time Period: 2005–2025 (20 years)  
- Geographic Coverage: Global  
- Frequency: Static historical analysis  

**Schema Highlights**
- **Identifiers** → `id`, `name`, `website`  
- **Business Info** → `industry`, `subindustry`, `team_size`, `all_locations`, `launched_at`  
- **YC Program Data** → `batch`, `status`, `top_company`, `stage`  
- **Current Metrics** → `isHiring`, `nonprofit`, `regions`  

**Data Quality**
- Completeness: 98.5%  
- Accuracy: Manually validated top classifications  
- Consistency: Standardized categories  
- Timeliness: Current as of 2025  

---

### 🔑 Insights from the Dashboard

---

## Executive Summary KPIs
- **Total Companies:** 5,407 
- **Overall Success Rate:** 1.68% (89 top companies)
- **Active Rate:** 69.6% (3,763 companies still operational)
- **Average Team Size:** 49 members
- **Program Growth:** 60x expansion (8 companies in 2005 → 480 in 2025)

---

### Business Insights
1.  **Scale vs. Quality Paradox:** The data indicates an inverse relationship between the program's growth and its success rate. As the number of companies per batch increased, the overall success rate declined.
2.  **Top Industries by Success Rate:** Based on the data, the industries with the highest success rates are:
    1.  **Fintech** (2.35%)
    2.  **Consumer** (2.27%)
    3.  **Industrials** (1.89%)
3.  **Temporal Evolution:** The program's success rate peaked in its early years (2005–2012) with rates above 6%, before dropping to below 2% from 2017 onwards.
4.  **Program Phases:** The program's evolution can be segmented into three distinct phases:
    * **Boutique Phase (2005–2012):** Small batch sizes with high success rates.
    * **Scaling Phase (2013–2018):** Rapid growth in company numbers coupled with a decline in success rates.
    * **Mass Market Phase (2019–2025):** Very large cohorts and a continued low success rate.

---

## 💡 Business Value

### For Entrepreneurs
- **Industry Selection:** Real Estate & B2B best probability  
- **Timing Strategy:** Batch history guides entry  
- **Competitive Benchmarking:** Understand market saturation  
- **Team Insights:** Optimal size/structure guidance  

### For Investors
- **Due Diligence:** Benchmarks by industry & year  
- **Portfolio Strategy:** Rebalance to strong sectors  
- **Risk Assessment:** Predictive batch/industry analysis  

### For YC Program Management
- **Batch Size Optimization**  
- **Industry Focus Programs**  
- **Expanded Success Metrics**  
- **Alumni Leverage for Mentorship**  

---

## 📈 Tools & Tech

- **Data Processing** → Excel, Power Query, Statistical Analysis, MySQL (data validation & KPI verification)  
- **Visualization** → Power BI Desktop, DAX, Power BI Service  
- **Development** → Git, GitHub, Markdown, VS Code  

### Advanced Features
- Interactive Filtering & Drilldowns  
- Dynamic Measures with DAX  
- Responsive Dashboard Design  
- Optimized Data Models  

---

## ⚡ Getting Started

### Prerequisites
- Power BI Desktop (latest version)  
- Microsoft Excel 2016+
- MySQL (for query-based validation of KPIs & metrics) 
- Basic BI and SQL knowledge  


