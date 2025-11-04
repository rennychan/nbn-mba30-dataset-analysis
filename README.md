# 📊 NBN MBA Dataset Analysis

## 📊 Power BI Dashboard Preview

![NBN MBA 2025 Dashboard](summary_dashboard.png)

👉 **[Download the interactive Power BI Dashboard
(.pbix)](./nbn_mba30_powerbi_dashboard.pbix)**

**Python + Power BI Analysis of ACCC NBN MBA Report 30 Dataset Broadband Performance Metrics**

---

### 📘 Overview
This project analyzes the *ACCC NBN MBA Report 30* dataset, which measures broadband performance (download, upload, latency) across different ISPs and access technologies (FTTP, HFC, FTTN, etc.).  
The goal is to identify national broadband trends, underperforming access types, and provider-level performance.

---

### 🧠 Key Insights
- **FTTP & HFC** maintain near-advertised speeds (> 95 Mbps).  
- **FTTN** underperforms most (~ 55–75 Mbps).  
- Independent ISPs (**Aussie Broadband**, **Superloop**) outperform incumbents.  
- National underperforming rate ≈ 4 – 5 %.

---

### 🧰 Tech Stack
- **Python** (`pandas`, `matplotlib`) for data processing & visualisation  
- **Google Colab** for interactive notebook execution  
- **Power BI** for dashboard creation and KPI reporting  
- **GitHub** for version control and portfolio presentation  

---

### 📊 Visual Outputs
- **Top 10 RSPs – Busy-hour Download (Mbps)**  
- **Download & Latency by Technology**  
- **Underperforming Services (%) by Technology**

*(See charts and CSVs in this repository.)*


---

### 🧩 Repository Structure

  --------------------------------------------------------------------------------------
  File                                 Description
  ------------------------------------ -------------------------------------------------
  `nbn_mba_analysis.ipynb`             Python notebook for data cleaning,
                                       transformation, and exploratory analysis

  `nbn_mba30_powerbi_dashboard.pbix`   Power BI dashboard file for visual exploration

  `summary_dashboard.png`              Static preview image of the final dashboard

  `kpIs.csv`, `rsp_summary.csv`,       Dataset files used in analysis
  `tech_summary.csv`,                  
  `network_health_by_tech.csv`         
  --------------------------------------------------------------------------------------

📍 Sydney, Australia  
🔗 [GitHub Profile](https://github.com/rennychan)
