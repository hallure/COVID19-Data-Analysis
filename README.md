# COVID19-Data-Analysis

# 🦠 COVID-19 Data Analysis: Exploring Trends, Vaccination Impact & Visual Insights

This project explores the global spread and impact of the COVID-19 pandemic by analyzing real-world data on cases, deaths, and vaccination rates. The goal is to uncover key trends, compare country-level responses, and visualize the effects of vaccination over time.

---

## 🧠 Project Objective

To clean, analyze, and visualize COVID-19 data using Python, with a focus on:

- Identifying trends in infections and deaths
- Comparing country-level impacts
- Understanding the relationship between vaccination and case/death rates

---

## 📁 About the Dataset

The dataset used includes daily COVID-19 statistics from multiple countries and contains the following key columns:

| Column       | Description |
|--------------|-------------|
| `DATE`       | Date of report |
| `country`    | Country or region |
| `NEW Cases`  | Number of new confirmed cases |
| `NEW_DEATHS` | Number of new reported deaths |
| `vaccinated` | Number of people who received at least one vaccine dose |

---

## 🧹 Data Cleaning Steps

- Removed rows with missing or null values in critical fields
- Standardized column names and corrected formats
- Converted date column to datetime format
- Filtered out inconsistent or irrelevant entries

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Questions Answered:

- Which countries recorded the highest number of daily and cumulative cases?
- What trends emerged in new cases and deaths across different time periods?
- How did vaccination efforts affect the number of new cases?
- Which regions showed a decline in cases post-vaccination?

---

## 📈 Visualizations

- **Line Plots**:  
  - Trends in daily new cases, deaths, and vaccinations over time  
- **Bar Charts**:  
  - Top countries by total cases, deaths, and vaccination rates  
- **Scatter Plots**:  
  - Correlation between vaccination rates and infection decline

All visualizations were created using `Matplotlib` and `Seaborn` in Google Colab.

---

## 🛠 Tools & Libraries

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab

---

## 💡 Key Insights

- Peak global cases were observed in 2021 across several countries
- Countries with high vaccination rates generally showed a downward trend in new cases
- Some countries with high case counts had relatively low vaccination rates, suggesting room for public health improvement
- The data emphasizes the importance of timely testing and widespread vaccination

---

## 🚀 How to Run

1. Open the project notebook in [Google Colab](https://colab.research.google.com)
2. Upload the dataset when prompted
3. Run each cell to perform cleaning, analysis, and visualization

---

## 📬 Contact

- GitHub: [yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
