# 🌍 Global Salary & Workforce Analytics Dashboard

> **Tableau Public | Interactive Business Intelligence Dashboard**

---

## 📌 Project Overview

This project presents an interactive **Global Salary & Workforce Analytics Dashboard** built in Tableau Public. It provides a comprehensive view of salary trends, employment patterns, company size distribution, and geographic spread of the global workforce — primarily focused on data professionals.

The dashboard enables HR professionals, data analysts, recruiters, and business leaders to explore compensation insights, workforce composition, and hiring trends across different countries, job titles, experience levels, and employment types.

---

## 🎯 Project Name Suggestions

| # | Name | Why It Works |
|---|------|--------------|
| 1 | **WorkForceGlobe** | Reflects global workforce & salary intelligence |
| 2 | **SalaryScope** | Clean, professional, focused on salary analysis |
| 3 | **TalentMetrics** | Emphasizes the analytics & talent data angle |
| 4 | **PayPulse Global** | Captures the dynamic, real-time feel of salary data |
| 5 | **CareerCompass Analytics** | Suggests guidance through workforce data |
| ⭐ | **GlobalPayIQ** | Best blend of global scope + salary + intelligence |

> ⭐ **Recommended:** `GlobalPayIQ` — short, memorable, and conveys both international scope and data intelligence.

---

## 📊 Dashboard Sections & Visual Analysis

### 1. 🗺️ Avg Salary By Map *(Top Right — World Choropleth Map)*

**What it shows:** A dark-themed world map highlighting countries by average salary level, using colour intensity to represent salary magnitude.

**Key Insights:**
- The **United States** appears as the highest-compensated region, shown by the deepest highlight.
- **Western Europe** (UK, Germany, France) and **India** also feature prominently.
- Many regions remain uncoloured, indicating limited or no data representation.
- A **"1 unknown"** label suggests one record with an unresolvable country code.

**Analytical Value:** Quickly identifies geographic salary disparities and highlights where global talent commands the highest compensation.

---

### 2. 🏠 Top 10 Employees Residence *(Bottom Left — Horizontal Bar Chart)*

**What it shows:** A ranked bar chart showing the top 10 countries where employees reside, measured by count.

**Country Rankings (Estimated from chart):**

| Rank | Country Code | Country | Approx. Count |
|------|-------------|---------|---------------|
| 1 | US | United States | ~330 |
| 2 | GB | United Kingdom | ~60 |
| 3 | IN | India | ~50 |
| 4 | CA | Canada | ~45 |
| 5 | DE | Germany | ~40 |
| 6 | FR | France | ~30 |
| 7 | ES | Spain | ~25 |
| 8 | GR | Greece | ~20 |
| 9 | JP | Japan | ~15 |
| 10 | BR | Brazil | ~10 |

**Key Insights:**
- The **US dominates** workforce residence by a significant margin — roughly 5–6x more than the next country (GB).
- Strong **English-speaking country** presence (US, GB, CA).
- Emerging tech markets like **India and Brazil** are represented, indicating global data talent spread.
- **European nations** (DE, FR, ES, GR) collectively form a significant segment.

---

### 3. 🔵 Employment Type & Experience Level *(Bottom Centre — Bubble Scatter Chart)*

**What it shows:** A matrix/bubble chart plotting salary (Y-axis: 100K–400K range) against employment type (Contract, Fixed Length, Full Time, Part Time) across experience levels (implied by bubble colour/size).

**Employment Type Columns:** Contract | Fixed Length | Full Time | Part Time

**Key Insights:**
- **Full Time** roles have the widest salary spread — from ~100K to nearly 400K — indicating high variability based on experience.
- **Contract** roles show mid-to-high salaries (~250K–400K range), suggesting senior/specialist contractors command premium pay.
- **Part Time** roles cluster at the lower salary bands (~100K–200K).
- **Fixed Length** roles appear at mid-range (~100K–200K).
- The chart reveals that **experience level** is a strong salary differentiator, especially within Full Time employment.

---

### 4. 🍩 Employment Type Distribution *(Bottom Right — Donut Chart)*

**What it shows:** Proportion of employees across employment types.

| Employment Type | Count | Share |
|----------------|-------|-------|
| Full Time | 509 | ~97.9% |
| Part Time | 5 | ~1.0% |
| Fixed Length | 1 | ~0.2% |

**Key Insights:**
- The dataset is **overwhelmingly Full Time** (509 out of 515 total employees).
- Negligible Part Time and Fixed Length representation suggests this dataset primarily captures **permanent, full-time data professionals**.
- The dominance of full-time roles is consistent with the tech/data industry norm.

---

### 5. 🏢 Company Size Distribution *(Bottom Right — Donut Chart)*

**What it shows:** The breakdown of companies employing the workforce by company size category.

| Company Size | Percentage |
|-------------|------------|
| Medium | 58.38% |
| Large | 31.02% |
| Small | 10.60% |

**Key Insights:**
- **Medium-sized companies** are the largest employer segment (58%), indicating that mid-scale organisations are the primary hirers of data professionals globally.
- **Large enterprises** account for ~31% — significant but not dominant.
- **Small companies** represent just ~10.6%, suggesting data roles are less common in early-stage or micro businesses.
- This distribution is typical for data science/analytics hiring patterns where mid-to-large firms have established data functions.

---

## 🔧 Dashboard Filters

The dashboard includes **three interactive filters** at the top, enabling dynamic data slicing:

| Filter | Purpose |
|--------|---------|
| **Employee Residence** | Filter all visuals by the employee's country of residence |
| **Job Title** | Narrow down data to specific roles (e.g., Data Scientist, ML Engineer) |
| **Company Size** | Filter by Small / Medium / Large company category |

These filters are cross-dashboard, meaning selecting a value in one chart automatically updates all others.

---

## 📈 Key Findings Summary

1. **US-centric workforce** — The United States represents the overwhelming majority of employee residences and likely the highest average salaries globally.
2. **Full-time dominance** — Over 97% of the workforce in this dataset holds full-time positions.
3. **Medium companies lead hiring** — More than half the workforce is employed at medium-sized organisations.
4. **Experience drives salary** — The scatter chart reveals wide salary bands within Full Time roles, heavily influenced by seniority/experience.
5. **Global but concentrated** — While data spans 10+ countries, the US, UK, and India account for the majority of entries.

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **Tableau Public** | Dashboard creation and visualisation |
| **Mapbox / OpenStreetMap** | Geospatial map rendering |
| **Dataset** | Global AI/Data Science Salary dataset (likely sourced from Kaggle or similar) |

---

## 📁 Dashboard Sheets

The workbook contains the following individual sheets feeding the dashboard:

- `Company Size`
- `Employment type`
- `Top 10 Employee Residents`
- `Employment type & Experience`
- `Avg Salary By Map`
- `Dashboard 1` *(the main compiled dashboard)*

---

## 👤 Intended Audience

- **HR & Talent Acquisition Teams** — Benchmark compensation and hiring market trends
- **Data Professionals** — Understand salary expectations by location and company size
- **Business Analysts** — Explore workforce composition across global markets
- **Recruiters** — Identify key talent geographies and salary benchmarks

---

## 📅 Dashboard Metadata

| Field | Detail |
|-------|--------|
| Created | May 2026 |
| Tool | Tableau Public |
| Total Records | ~515 employees |
| Geography Scope | Global (10+ countries) |
| Primary Domain | Data Science / AI / Tech Workforce |

---

*Dashboard screenshot captured: 15-05-2026 at 16:35*
