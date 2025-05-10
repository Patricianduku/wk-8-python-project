# COVID-19 Data Analysis Project

> Analysis of OWID COVID-19 dataset using Python libraries to explore and visualize global pandemic trends.

## 🎯 Objectives

- Clean and preprocess COVID-19 data
- Analyze data for selected countries (Kenya, United States, India)
- Create visualizations for:
  - Total cases and deaths
  - Daily new cases
  - Death rate analysis
  - Top affected countries
  - Variable correlations

## 🧰 Tech Stack

- **Python 3.x**
- **Key Libraries:**
  - Pandas (data manipulation)
  - Matplotlib (basic plotting)
  - Seaborn (advanced visualization)

## ▶️ Getting Started

### Prerequisites

1. Python 3.x installed
2. Required libraries: `pandas`, `matplotlib`, `seaborn`

### Installation

```bash
pip install pandas matplotlib seaborn
```

### Dataset Setup

1. Download `owid-covid-data.csv` from [Our World in Data](https://ourworldindata.org/covid-deaths)
2. Place the CSV file in your project directory

## 📊 Visualization Features

### 1. Line Charts
- Track temporal trends in:
  - Total COVID-19 cases
  - Total deaths
  - New daily cases

### 2. Bar Chart
- Top 10 countries by total cases
- Latest date comparison

### 3. Heatmap
- Correlation analysis between:
  - Cases
  - Deaths
  - Reproduction rate
  - Other health indicators

## 💡 Key Insights

1. **Death Rate Variations**
   - Differences across countries
   - Impact of healthcare systems
   - Effects of virus variants

2. **Case Patterns**
   - Clear visualization of pandemic waves
   - Rolling averages for trend analysis

3. **Data Quality**
   - Missing value handling using:
     - `dropna()`
     - `fillna()`
     - Interpolation methods

## 📝 Project Structure

```
project/
│
├── data/
│   └── owid-covid-data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
└── README.md
```

## 🤝 Contributing

Contributions welcome! Please feel free to submit a Pull Request.

