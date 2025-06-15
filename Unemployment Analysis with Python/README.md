# Unemployment Analysis in India (2020–2021)

This project presents a data-driven analysis of unemployment trends in India during the COVID-19 pandemic. It focuses on visualizing and understanding the unemployment patterns across different states and areas (urban vs rural), and interpreting the effects of the pandemic on employment dynamics.

## 🌐 Project Objective

To analyze, visualize, and derive insights from unemployment data in India during the COVID-19 period (2020–2021) using Python.

## 📈 Features

* Time-series analysis of unemployment rates
* State-wise unemployment comparison
* Rural vs Urban unemployment rate breakdown
* Scatter plot between Employment Rate vs Labour Participation
* Forecasted unemployment trend using historical data
* Professional PDF report generation with insights and visuals

## ⚙️ Tools & Technologies

* **Programming Language:** Python
* **Libraries:** pandas, matplotlib, seaborn, fpdf
* **IDE:** Jupyter Notebook / VS Code
* **Visualization:** Matplotlib, Seaborn
* **Reporting:** FPDF (PDF report generation)

## 📊 Dataset

* Format: CSV
* Fields include: `Region`, `Date`, `Frequency`, `Estimated Unemployment Rate (%)`, `Estimated Employed`, `Estimated Labour Participation Rate (%)`,`Area`
* Source: Public unemployment dataset from CMIE or similar authority

## 📅 Timeline of Work

1. Data Collection & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Visualizations & Plotting
4. Inference Drawing
5. PDF Report Compilation
6. README & Project Structuring

## 📂 Folder Structure

```
Unemployment_Analysis_Project/
│
├── data/
│   └── unemployment.csv
├── Output/
│   ├── Plot1.png
│   ├── Plot2.png
│   └── Unemployment_Analysis_Report.pdf
├── src/
│   └── analysis_script.py
├── Report.md (or Report.pdf)
├── requirements.txt
└── README.md
```

## 🔧 How to Run

1. Clone or download the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the main notebook `Unemployement_in_India.ipynb`
4. Check the `Output/` folder for the generated plots and report

## 🔧 Requirements

```
pandas
matplotlib
seaborn
fpdf
```

## 📖 Key Insights Summary

* Unemployment spiked in April–May 2020 due to COVID-19
* Urban unemployment was consistently higher than rural
* Tripura, Haryana, and Jharkhand were most affected
* Labour force participation doesn't always mean employment
* Forecasting suggests recovery post-2021 with uncertainty


## 🙋‍♂️ Author

* Anshuman Singh
* GitHub: [Anshuman-cs50](https://github.com/Anshuman-cs50)
