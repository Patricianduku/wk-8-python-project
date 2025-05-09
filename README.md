COVID-19 Data Analysis with Pandas, Matplotlib, and Seaborn
This project analyzes the OWID COVID-19 dataset using Python libraries to explore and visualize trends in cases, deaths, and other health indicators across multiple countries.

🎯 Objectives
Clean and preprocess COVID-19 data.

Filter and focus on selected countries (Kenya, United States, India).

Visualize trends in total cases, total deaths, and new daily cases.

Calculate and analyze the COVID-19 death rate.

Highlight top countries by total cases using bar charts.

Optionally explore variable relationships using a heatmap.

🧰 Tools and Libraries Used
Python 3

Pandas – for data manipulation and cleaning

Matplotlib – for basic plotting

Seaborn – for enhanced data visualization

▶️ How to Run the Project
Download the Dataset:
Get owid-covid-data.csv from Our World in Data and place it in your working directory.

Run Jupyter Notebook:

Open Jupyter Notebook or JupyterLab.

Create a new notebook and copy in the code provided in logical steps:

Load and inspect the dataset.

Filter countries.

Clean data and handle missing values.

Plot visualizations.

Run Each Cell Step by Step:
The project is structured into logical steps:

Data loading and inspection

Filtering and cleaning

Plotting total cases, deaths, and daily new cases

Calculating death rate

Bar chart and (optional) heatmap

📊 Visualizations Included
Line Charts:
Track total COVID-19 cases, deaths, and new daily cases over time for selected countries.

Bar Chart:
Show top 10 countries by total cases on the latest date.

Heatmap:
Visual correlation analysis between key numerical features (cases, deaths, reproduction rate, etc.)

💡 Insights and Reflections
Death Rate Trends: The death rate varies across countries and time, revealing the impact of healthcare systems, virus variants, and interventions.

Peaks in New Cases: Rolling averages of daily new cases highlight pandemic waves more clearly.

Data Gaps: Handling missing values is essential — we use dropna(), fillna(), and interpolation for robustness.

Visualization Power: Combining pandas, matplotlib, and seaborn allows quick exploratory data analysis with high clarity.

