 
# 🏦 Bank Marketing Funnel & Conversion Performance Analysis
### Future Interns – Data Science & Analytics Task 3 (2026)

---

## 📌 Project Overview

This project performs a comprehensive **marketing funnel and conversion analysis** on the UCI Bank Marketing Dataset. The goal is to help a Portuguese bank understand how telemarketing contacts convert into term deposit subscriptions — identifying top-performing segments, drop-off points, and actionable growth levers.

---

## 📁 Repository Structure

```
bank-marketing-funnel-analysis/
│
├── data/
│   ├── bank-additional-full.csv     # Full dataset (41,188 records)
│   ├── bank-additional.csv          # 10% sample (4,119 records)
│   └── bank-additional-names.txt    # Dataset documentation
│
├── Bank_Marketing_Funnel_Analysis.xlsx   # Main deliverable (Excel dashboard)
│
└── README.md
```

---

## 📊 Dataset

**Source:** [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

**Citation:**
> S. Moro, P. Cortez and P. Rita. *A Data-Driven Approach to Predict the Success of Bank Telemarketing.* Decision Support Systems, 2014. doi:10.1016/j.dss.2014.03.001

| Attribute | Details |
|---|---|
| Records | 41,188 |
| Features | 20 input + 1 output |
| Period | May 2008 – November 2010 |
| Target | `y` — Did the client subscribe a term deposit? (yes/no) |

---

## 📈 Excel Workbook – Sheet Guide

| Sheet | Contents |
|---|---|
| **Executive Summary** | KPI cards, full funnel overview, 6 key recommendations |
| **Raw Data (Sample)** | 2,000 randomly sampled records with formatting |
| **Channel Analysis** | Cellular vs Telephone CVR comparison + chart |
| **Monthly Analysis** | Month-by-month CVR ranking + performance tier + chart |
| **Job Segment Analysis** | CVR by occupation, tiered into Tier 1/2/3 |
| **Age & Campaign Analysis** | CVR by age group and number of campaign contacts |
| **Previous Campaign Impact** | Impact of prior campaign outcome on conversion |

---

## 🔍 Key Findings

### 🎯 Overall Funnel
| Stage | Count | CVR |
|---|---|---|
| Total Contacts | 41,188 | 100% |
| Cellular Contacts | 26,144 | 14.74% |
| Previously Contacted | 5,625 | 26.65% |
| Prior Success Clients | 1,373 | **65.11%** |
| **Final Conversions** | **4,640** | **11.27%** |

### 📱 Channel Performance
- **Cellular:** 14.74% CVR — **2.8x better** than telephone (5.23%)
- Cellular contacts make up 63.5% of total outreach

### 📅 Best Months to Campaign
- March (50.5%), September (44.9%), October (43.9%), December (48.9%) — all >40% CVR
- May/July/August show <10% CVR despite being the highest-volume months

### 💼 Top Job Segments
1. Students — 31.4% CVR
2. Retired — 25.2% CVR
3. Unemployed — 14.2% CVR

### 🔄 Previous Campaign Outcome
- Prior **success** → **65.1% CVR** (6x the overall average)
- Prior **failure** → 14.2% CVR (still above average — worth retrying)
- **No prior contact** → 8.8% CVR (baseline)

### 📞 Campaign Contact Depth
- 1 contact → 13% CVR
- 6+ contacts → 5.5% CVR
- **Diminishing returns begin after 3 contacts**

---

## 💡 Actionable Recommendations

1. **Prioritise cellular outreach** — reallocate budget from telephone to cellular channel
2. **Seasonal campaign planning** — concentrate launches in Mar, Sep, Oct, Dec
3. **Segment targeting** — build specific campaigns for students and retirees
4. **Re-engagement workflow** — fast-track prior-success clients with VIP outreach
5. **Contact frequency cap** — limit to ≤3 contacts per client per campaign
6. **Age-based messaging** — tailor product communication for <25 and 65+ demographics

---

## 🛠️ Tools Used

- **Python** (pandas, openpyxl) — data processing and Excel generation
- **Microsoft Excel / LibreOffice Calc** — dashboard viewing and analysis
- **UCI Machine Learning Repository** — dataset source

---

## 🚀 How to Open

1. Download `Bank_Marketing_Funnel_Analysis.xlsx`
2. Open with **Microsoft Excel** or **LibreOffice Calc**
3. Start from the **Executive Summary** sheet
4. Navigate through sheets using the tabs at the bottom

---

*This project was completed as part of the Future Interns Data Science & Analytics Program, Task 3 (2026).*
