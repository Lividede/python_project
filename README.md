# 🦠 COVID-19 Global Data Analysis & Visualization

A data-driven project analyzing global COVID-19 trends using Python. This project uses real-world data to explore time-based trends in cases, deaths, and vaccinations. It offers meaningful insights across countries and includes powerful data visualizations.

---

## 🚩 Project Objectives

- 📥 Import and clean real-world COVID-19 global data.
- 📊 Analyze trends in cases, deaths, and vaccination rollouts over time.
- 🌍 Compare metrics across multiple countries and regions.
- 📈 Visualize key indicators using line charts, bar plots, and (optionally) maps.
- 📝 Communicate insights effectively using code, charts, and narrative in a Jupyter Notebook.

---

## 📦 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- `pandas` – data manipulation
- `matplotlib` – data visualization
- `seaborn` – enhanced chart styling
- *(Optional tools you may add)*:
  - `plotly.express` – for interactive or choropleth maps
  - `geopandas` – geospatial analysis

---

## 🗂️ Project Segments

### 1️⃣ Data Collection
- Data source: [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-cases)
- File used: `owid-covid-data.csv`

### 2️⃣ Data Loading & Exploration
- Loaded the dataset using `pandas.read_csv()`
- Checked structure: `.columns`, `.head()`, and missing values with `.isnull().sum()`

### 3️⃣ Data Cleaning
- Filtered data for countries of interest (e.g., Kenya, USA, India)
- Converted the `date` column to datetime format
- Handled missing values with `.fillna()` and interpolation

### 4️⃣ Exploratory Data Analysis (EDA)
- Plotted time series for total cases and deaths
- Compared daily new cases across countries
- Calculated death rates and visualized trends

### 5️⃣ Visualizing Vaccination Progress
- Tracked vaccination rollout over time
- Compared percent of vaccinated population between countries

### 6️⃣ *(Optional)* Choropleth Mapping
- Visualized global vaccination/case density using country-level data

### 7️⃣ Insights & Reporting
- Summarized findings using Markdown cells
- Highlighted trends, anomalies, and regional differences

---

## ▶️ How to Run the Project

1. Clone this repository or download the `.ipynb` notebook.
2. Make sure you have the following Python packages installed:
   ```bash
   pip install pandas matplotlib seaborn
