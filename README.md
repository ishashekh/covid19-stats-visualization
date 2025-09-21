# COVID-19 Descriptive Statistics Project

This project analyzes COVID-19 daily cases and deaths using the [Our World in Data dataset](https://catalog.ourworldindata.org/garden/covid/latest/cases_deaths/cases_deaths.csv).  
It demonstrates a full **data analyst workflow**: cleaning, descriptive statistics, visualization, dashboards, and anomaly detection.

---

## 🚀 Steps Covered
1. **Data Collection** – Load dataset from OWID  
2. **Data Understanding** – Explore columns, missing values, anomalies  
3. **Data Cleaning** – Fix negatives, select relevant columns, drop nulls  
4. **Data Preparation** – Filter by country (default: Canada), sort by date  
5. **Descriptive Statistics** – Mean, median, mode, std, percentiles  
6. **Visualizations** – Histogram, boxplot, density, yearly distributions  
7. **KPI Dashboard** – Rolling averages, yearly averages, peak days  
8. **Export Peak Days** – Save top 30 cases/deaths as CSV  
9. **Two-Country Comparison** – Compare Canada vs US  
10. **AI Add-On** – Isolation Forest anomaly detection for unusual days  

---

## ⚙️ Setup & Run

Clone the repo and create a virtual environment:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

python -m venv .venv
source .venv/bin/activate   # mac/linux
# or .venv\Scripts\activate # windows

pip install -r requirements.txt