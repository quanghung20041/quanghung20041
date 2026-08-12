<h1 align="center">Hi, I'm Quang Hung 👋</h1>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=2F80ED&center=true&vCenter=true&width=560&lines=Turning+raw+data+into+decisions;Python+%7C+SQL+%7C+Power+BI+%7C+Excel;Building+pipelines%2C+dashboards+%26+forecasts" alt="Typing SVG" />
</p>

---

### 💁‍♂️ About Me

I'm an International Business Administration student with a strong interest in **Data Analytics and Business Analytics**. I work with real operational and business datasets - sales, HR, and distribution data - to build data pipelines, dashboards, and forecasting models that support decision-making.

I'm currently seeking **Data Analyst / Business Analyst** roles where I can keep developing my analytical, technical, and business problem-solving skills.

- 🔭 Recently built an end-to-end **Bronze → Silver → Gold data warehouse** and a **SKU-level ML sales forecasting pipeline**
---

### 🛠️ Skills

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
</p>

---

### 📂 Featured Projects

#### 📦 [VietDist Analytics Project](https://github.com/quanghung20041/VietDist_Analytics_Project)
End-to-end **Bronze → Silver → Gold data warehouse** for a Vietnamese FMCG distributor - consolidating 10 raw sales, HR, and distributor sources (~165K records) into a governed PostgreSQL warehouse to track sales rep performance against monthly targets.
- Built a **star schema** with a true **SCD Type 2** employee dimension and versioned sales targets for point-in-time analysis
- Profiled every source for nulls/duplicates before transforming, with all findings and decisions documented
- Delivered `mart_sales_vs_target`, a warehouse-ready mart comparing actual vs. quota revenue, quantity, and new customers by employee

**Tools:** Python, SQL, PostgreSQL, SQLAlchemy

#### 📈 [Sales Forecasting by SKU Project](https://github.com/quanghung20041/Sales_Forecasting_by_SKU_Project)
Daily, SKU-level sales forecasting pipeline for a multi-channel e-commerce distributor (676 SKUs, 6 channels, ~48K transactions) - from EDA through feature engineering, model tuning, and explainability.
- Engineered 23 time-series features (lags, rolling windows, calendar effects) and compared a **Prophet baseline** against **LightGBM tuned with Optuna** (MAE improved from 181.2 → 174.7)
- Used **SHAP** to explain predictions at both global and single-forecast level, surfacing a systematic underprediction bias that matters for inventory planning
- Evaluated on a genuine time-based holdout split (not random) to avoid leakage

**Tools:** Python, pandas, LightGBM, Prophet, Optuna, SHAP

#### 📊 [HR Workforce Dashboard](https://github.com/quanghung20041/HR-Workforce-Dashboard)
Interactive Power BI dashboard consolidating 7 related HR tables (298 employees) into a star-schema model to analyze turnover, headcount, and recruitment channel effectiveness.
- Found overall turnover of **34.9%**, with Production driving the majority of attrition at **40.89%**
- Built DAX measures for turnover rate, tenure, engagement, and recruitment source performance
- Two report views: an Executive Summary for leadership and a filterable Workforce Database page for manager-level drill-down

**Tools:** Power BI, DAX, Power Query, Excel

---

<p align="center"><i>Thanks for stopping by - always open to feedback and DA/BA opportunities!</i></p>
