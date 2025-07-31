
# 🌍 Tracking Maternal Health Progress Toward SDG 3.1: A Global Data Analysis

## 📌 Project Overview
This project analyzes maternal health indicators to assess global progress toward the **Sustainable Development Goal (SDG) 3.1**, which aims to reduce the global **maternal mortality ratio (MMR)** to less than **70 per 100,000 live births by 2030**.

The analysis was conducted using the **AI Kosh Dataset** from [data.gov.in](https://www.data.gov.in/resource/sustainable-development-goals-national-indicator-framework-version-31-2021), and visualizations were created using **IBM Cloud Lite's Data Refinery** — a no-code data preparation and visualization tool.

## 🎯 Objectives

- Monitor maternal health outcomes using key health indicators.
- Identify disparities between countries and income groups.
- Visualize trends in maternal mortality, healthcare access, and expenditure.
- Generate insights to inform policy and action.

## 🧰 Technologies Used

- ✅ IBM Cloud Lite
- ✅ IBM Watson Studio (Data Refinery)
- ✅ AI Kosh Dataset from [data.gov.in](https://www.data.gov.in/)
- ❌ No code (Python or R) was used — entire project done via Data Refinery UI

## 📊 Dataset Features

- Maternal Mortality Ratio (MMR)
- Births attended by skilled health personnel (%)
- Antenatal care coverage
- Adolescent birth rate
- Health expenditure (% of GDP)
- Country and region-wise metadata

## 📈 Visualizations Created

The following charts were generated using IBM Data Refinery:

- **Maternal Mortality Ratio by Country** – Bar chart
- **Health Expenditure vs MMR** – Scatter plot
- **Births Attended by Skilled Personnel (%)** – Comparative bar chart
- **Antenatal Care Coverage Trends** – Line chart

📁 View them in the [`charts/`](charts/) folder.

## 🔍 Key Insights

- Countries with higher skilled birth attendance consistently show lower MMR.
- Sub-Saharan African regions face higher maternal mortality due to limited healthcare access.
- Health expenditure positively correlates with improved maternal health outcomes.
- Adolescent birth rate is a critical influencing factor in maternal health.

## 📂 Project Structure

```
SDG_3.1_Maternal_Health_Analysis/
├── README.md
├── cleaned_data.csv
├── Project_Description.pdf
├── charts/
│   ├── chart1.png
│   └── chart2.png
```

## 📎 Dataset Source

- 📥 [AI Kosh SDG Dataset - Data.gov.in](https://www.data.gov.in/resource/sustainable-development-goals-national-indicator-framework-version-31-2021)

## 📌 Conclusion

This analysis highlights the disparities in maternal health outcomes across different countries and suggests that stronger investment in healthcare infrastructure, especially skilled birth attendance and antenatal care, is crucial to achieving SDG 3.1 by 2030.

## 🔭 Future Scope

- Use IBM Watson Studio notebooks (Python/R) for predictive modeling
- Create a real-time dashboard using Streamlit or Dash
- Expand the dataset to include recent years and more countries
