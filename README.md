# Climate_Change_EDA_DataAnalysis.

# Climate Change Data Analysis for Policy Insights

## Project Overview
This project explores **global climate change indicators** to provide actionable insights for policymakers. Acting as a data consultant for an international environmental agency (like the UN Environment Programme), the goal is to perform **Exploratory Data Analysis (EDA)** to uncover patterns, trends, and relationships that inform policies for mitigating climate risks and promoting sustainability.  

The analysis focuses on **understanding the data deeply** rather than applying machine learning models. Insights are translated into **policy recommendations** to address emissions, renewable energy adoption, forest conservation, and population vulnerability.

---

## Problem Statement
Climate change is accelerating, with rising temperatures, extreme weather events, and environmental degradation affecting billions of people. Governments and organizations require **evidence-based policies** to mitigate impacts, such as reducing emissions, protecting ecosystems, and enhancing resilience.  

This project explores how factors like **CO2 emissions, renewable energy usage, forest area, and extreme weather events** interact across countries and years. The goal is to highlight opportunities for policy interventions to build a more resilient world.

---

## Dataset
**Source:** [Kaggle - Climate Change Dataset](https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset)  

**Key Columns:**
- `Year` – Year of the data point  
- `Country` – Country or region  
- `Average Temperature (°C)` – Average annual temperature  
- `CO2 Emissions (Tons/Capita)` – Per-capita carbon dioxide emissions  
- `Sea Level Rise (mm)` – Annual sea level increase  
- `Rainfall (mm)` – Total annual rainfall  
- `Population` – Total population  
- `Renewable Energy (%)` – Percentage of energy from renewable sources  
- `Extreme Weather Events` – Number of extreme events (storms, floods, etc.)  
- `Forest Area (%)` – Percentage of land covered by forests  

**Notes:** The dataset may contain inconsistencies (e.g., outliers in temperature or population). These have been addressed during data preparation to simulate real-world data challenges.

---

## Analysis Framework
The EDA was conducted using a structured roadmap inspired by professional analytics workflows:

1. **Data Understanding:**  
   - Load dataset, review structure, missing values, and basic statistics.  
   - Identify anomalies or cleaning needs.  

2. **Data Preparation:**  
   - Handle duplicates, outliers, and inconsistencies.  
   - Group or normalize data as needed.  

3. **Question Formulation & Exploration:**  
   - 10 targeted EDA questions covering univariate, bivariate, and multivariate analyses.  
   - Visualizations include **histograms, scatter plots, bar plots, box plots, and heatmaps**.  

4. **Insight Generation:**  
   - 5–7 key insights derived from correlations, trends, and distributions.  
   - Linked insights to **policy implications**.  

5. **Policy Recommendations:**  
   - 3–5 actionable recommendations for environmental agencies based on the insights.

---

## Key Insights

| Insight Focus | Data Support | Policy Implication |
|---------------|--------------|------------------|
| Mitigation Leverage | CO2 vs Extreme Events Correlation: r=+0.54 | Focus on emission reduction in high-risk zones. Reducing CO2 directly lowers extreme event frequency. |
| Climate Equity | Avg Temp vs CO2 Correlation: r=−0.57 | Prioritize adaptation funding for vulnerable high-temperature, low-emission countries. |
| Natural Resilience Value | Forest Area vs Extreme Events Correlation: r=−0.26 | Incentivize forest area expansion to provide protective buffers against climate shocks. |
| Ineffective Renewable Transition | Renewable Energy vs CO2 Correlation: r=+0.27 | Shift policy from mere installation targets to mandates that displace fossil fuels. |
| Concentrated Human Risk | Vulnerability Analysis (Extreme Weather vs Population Density) | Target adaptation resources toward densely populated, high-risk coastal regions. |
| Global Warming Urgency | Temperature & Sea Level Trends | Accelerated trends require shorter intervention cycles (5-year) in international agreements. |

---

## Policy Recommendations for the UN Environmental Programme

### **Proposal 1: Emissions Displacement Mandate**
- **Action:** Global Carbon Efficiency Tax on Top 10 Polluting Countries if increased Renewable Energy adoption fails to reduce CO2 emissions over 5 years.  
- **Rationale:** Ensures renewables actively displace fossil fuels, addressing both high CO2 emissions and extreme event risks.

### **Proposal 2: Resilience for Conservation Fund**
- **Action:** Establish a fund conditioned on nations increasing Forest Area (%) by at least 1% per year to access adaptation aid.  
- **Rationale:** Nature-based solutions enhance ecosystem resilience while mitigating extreme weather impacts.

### **Proposal 3: Global Climate Equity Transfer**
- **Action:** Direct funding from high-emission, moderate-temperature countries to vulnerable regions with high population density and extreme weather exposure.  
- **Rationale:** Ensures climate justice by targeting resources to the most vulnerable populations.

---

## Visualizations
All plots generated are saved in the `plots/` folder:

- Bar Plots: Top Polluters, Renewable Leaders  
- Scatter Plots: Vulnerability Analysis, CO2 vs Extreme Events  
- Box Plots: CO2 Emissions by Population Groups  
- Histograms: Temperature & Rainfall Distribution  
- Heatmaps: Correlation Matrix of Climate Indicators  

---

## Libraries Used
- **Python 3.x**  
- **pandas** – data manipulation  
- **numpy** – numerical operations  
- **matplotlib & seaborn** – data visualization  

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/GAURAVSINGH17/climate-data-analysis.git

2. Install required libraries:

pip install pandas numpy matplotlib seaborn


3. Open the Jupyter Notebook and run all cells to reproduce the analysis.

Author

Gaurav Singh .
