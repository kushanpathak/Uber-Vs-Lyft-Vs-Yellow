# 🚖 NYC Fare Analysis: Uber vs Lyft vs Yellow Cabs

## 📌 Project Overview

This project analyzes and compares ride fares across **Uber, Lyft, and Yellow Cabs in New York City (NYC)**. The goal is to help customers identify the most cost-effective transportation option based on **time of day, weekday vs weekend trends, and overall fare patterns**.

By leveraging historical trip data from **2021, 2022, and 2023**, this analysis provides actionable insights into how ride prices fluctuate and when each service is most economical.

---

## 🎯 Objectives

* Compare fare trends between Uber, Lyft, and Yellow Cabs
* Identify cheapest ride options based on:

  * Time of day (peak vs off-peak hours)
  * Weekdays vs weekends
* Analyze yearly trends (2021–2023)
* Provide insights to help commuters make informed travel decisions

---

## 📊 Data Sources

* Official NYC datasets (2021, 2022, 2023)
* Data format: **Parquet files**
* Data includes:

  * Pickup & drop-off timestamps
  * Fare amounts
  * Trip distances
  * Vendor/service provider details

---

## 🛠️ Tech Stack

* **Python**

  * Pandas (data manipulation)
  * NumPy (numerical operations)
  * Matplotlib / Seaborn (visualization)
* **Parquet** (efficient storage and processing)
* Jupyter Notebook / Python scripts for analysis

---

## 🔄 Data Processing Workflow

1. **Data Ingestion**

   * Loaded Parquet files for all three years
2. **Data Cleaning**

   * Handled missing/null values
   * Removed outliers in fare amounts
3. **Feature Engineering**

   * Extracted:

     * Hour of day
     * Day of week
     * Weekend vs weekday flag
4. **Aggregation**

   * Grouped data by:

     * Time intervals
     * Service provider
5. **Analysis**

   * Compared average fares across:

     * Time slots
     * Days
     * Years

---

## 📈 Key Insights

* 🚦 **Peak hours (morning & evening)** show higher surge pricing for Uber and Lyft
* 🚕 **Yellow Cabs** tend to be more stable and sometimes cheaper during peak times
* 🌙 **Late-night rides** often show higher variability in rideshare pricing
* 📅 **Weekends** generally have higher fares due to demand spikes
* 📉 Certain time windows consistently offer **lower-cost travel options** depending on the service

---

## 📊 Sample Analysis Dimensions

* Fare comparison by hour of day
* Fare comparison: weekday vs weekend
* Year-over-year fare trends
* Service-wise pricing distribution

---

## 📁 Project Structure

```
nyc-fare-analysis/
│
├── data/
│   ├── 2021/
│   ├── 2022/
│   └── 2023/
│
├── notebooks/
│   └── analysis.ipynb
│
├── scripts/
│   └── data_processing.py
│
├── visuals/
│   └── charts/
│
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/nyc-fare-analysis.git
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn pyarrow
   ```

3. Run the analysis:

   * Open Jupyter Notebook:

     ```bash
     jupyter notebook
     ```
   * Run `analysis.ipynb`

---

## 📌 Future Enhancements

* Add real-time pricing APIs for live comparison
* Build an interactive dashboard (Power BI / Tableau)
* Incorporate weather and event-based pricing impact
* Predict fare trends using machine learning

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit pull requests.

---

## 📬 Contact

For questions or collaboration, feel free to reach out.

---

⭐ If you found this project useful, consider giving it a star!
