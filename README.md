# 🎯 Problem Statement
This project uses a dataset with key health indicators across countries to explore global health trends. We analyze factors such as health expenditure, life expectancy, mortality rates, and disease prevalence to uncover insights that could shape health policy and improve outcomes, especially in underrepresented regions.

---

# 🗂️ Dataset Overview
The dataset contains global health indicators spanning multiple years. Key features include:

## 1. Country & Time Data
- **`country`**: Country name (e.g., "USA")
- **`country_code`**: ISO country code (e.g., "US")
- **`year`**: Year of data reporting

## 2. Health Indicators
- **`health_exp`**: Health expenditure (% of GDP)
- **`life_expect`**: Life expectancy at birth (total years)
- **`maternal_mortality`**: Maternal mortality rate (deaths per 100,000 live births)
- **`infant_mortality`**: Infant mortality rate (deaths per 1,000 live births)
- **`neonatal_mortality`**: Neonatal mortality rate (deaths per 1,000 live births)
- **`under_5_mortality`**: Under-5 mortality rate (deaths per 1,000 live births)
- **`prev_hiv`**: Prevalence of HIV (% of population)
- **`inci_tuberc`**: Tuberculosis incidence (cases per 100,000 people)
- **`prev_undernourishment`**: Prevalence of undernourishment (% of population)

---

# 📍 Target Variable
**Indicator Values**: Each row represents a health indicator for a given country in a specific year. The dataset provides insights into global health trends and relationships between health factors across countries.

---

# ✨ Dataset Insights
- The dataset spans multiple countries and years, offering a longitudinal view of global health.
- Indicators such as health expenditure, life expectancy, and mortality rates help understand global health outcomes.
- The target variables focus on health outcomes like mortality rates and disease prevalence.

---

# 📈 Visualization Insights
We will visualize the data using several plots to reveal global health trends, including:

- **Histograms** to compare health expenditures and mortality rates across countries.
- **Line plots** to observe trends in life expectancy and maternal mortality over time.
- **Correlation heatmaps** to explore relationships between health spending, life expectancy, and disease prevalence.

---

## 🔧 Installation
1. Clone the repository:
   git clone https://github.com/Fayez302/Global_health_Indicators_Analysis.git
3.  Install required libraries
   pip install -r requirements.txt
4. Open the Jupyter Notebook:
   Global Health Indicators Analysis.ipynb

![Python](https://img.shields.io/badge/Python-3.8-blue)
