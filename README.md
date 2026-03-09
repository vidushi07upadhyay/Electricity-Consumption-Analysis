# Plugging into the Future: Electricity Consumption Patterns Analysis ⚡


---

# Project Overview

**Plugging into the Future: Electricity Consumption Patterns Analysis** explores electricity usage trends to uncover patterns in energy demand, regional consumption, and long-term growth.

The project analyzes historical electricity data and presents insights through interactive visualizations built using Tableau Public.

The objective is to understand:

- How electricity consumption changes over time
- When peak demand periods occur
- Regional variations in electricity usage
- Sector-wise energy consumption patterns
- Long-term trends affecting sustainable energy planning

This project was developed as part of a **Data Analytics with Tableau course offered through SkillWallet (via college)**.

---

# Key Questions Explored

- How does electricity consumption vary across years and time periods?
- What are the peak electricity demand periods?
- How does electricity usage differ across Indian states?
- Which sectors consume the most electricity?
- What insights can be drawn for future energy planning and efficiency?

---

# Technologies & Tools Used

| Tool | Purpose |
|-----|------|
| MySQL Workbench | Data storage and querying |
| CSV Export | Data transfer from MySQL to Tableau |
| Tableau Public | Data visualization & dashboards |
| Flask | Web application for dashboard embedding |
| HTML / CSS | User interface design |

**Note:**  
Tableau Public does not support direct database connections. Therefore, data was exported from MySQL Workbench as CSV before visualization.

---

# Dataset

**File in Repository:**  
`Consumption.csv`

The dataset contains electricity consumption records used to analyze trends and patterns.

### Key Columns (Typical Fields)

- Date / Timestamp
- Electricity Consumption (kWh / MW)
- State / Region
- Time of Day / Hour
- Consumption Category
  - Residential
  - Industrial
  - Agricultural
  - Commercial

Datasets like this are commonly derived from:

- Government electricity reports
- Energy statistics datasets
- Open data repositories
- Course-provided educational datasets

---

# Project Structure

```
Electricity-Consumption-Tableau-Analysis
│
├── Consumption.csv
│
├── app.py
│
├── requirements.txt
│
├── templates
│   └── index.html
│
└── README.md
```

### Folder Details

**Consumption.csv**  
Main dataset used for analysis.

**templates/index.html**  
Frontend UI used to display the embedded Tableau dashboard.

**app.py**  
Flask application used to serve the webpage.

**requirements.txt**  
Python dependencies required for the web application.

---

# Tableau Dashboard

The project includes an interactive dashboard built using Tableau Public.

### Live Interactive Dashboard

View the interactive visualization here:

https://public.tableau.com/views/Electricity_17729082156350/StoryonElectricityConsumptioninIndia

The dashboard includes:

- National electricity consumption trends
- State-wise electricity usage map
- Sector-wise consumption analysis
- Interactive filters and time exploration

---

# Key Visualizations & Insights

### 1. National Electricity Consumption Trend

A time-series line chart showing the growth of electricity consumption over the years.

**Insights**

- Overall electricity demand has steadily increased.
- Significant growth observed in recent years due to economic expansion and population growth.

---

### 2. State-Wise Electricity Consumption Map

A choropleth map of India showing electricity usage across states.

**Insights**

- Highly industrialized states show greater electricity demand.
- Regional differences highlight infrastructure and economic development variations.

---

### 3. Sector-Wise Electricity Consumption

A pie chart / stacked bar chart showing electricity usage across sectors:

- Residential
- Industrial
- Agricultural
- Commercial

**Insights**

- Industrial and residential sectors account for the majority of electricity usage.

---

### 4. Time-Based Usage Patterns

Hourly and yearly trend charts help identify **peak demand periods**, which are important for energy planning and grid management.

---

# How the Analysis Was Built

1. Raw electricity data was imported into MySQL Workbench.
2. Relevant data tables were exported as CSV files.
3. CSV data was connected to Tableau Public.
4. Data cleaning and preparation were performed:
   - Date formatting
   - Null value handling
   - Calculated fields
5. Multiple visualizations were created:
   - Time-series trend charts
   - State maps
   - Sector breakdown charts
6. Visualizations were combined into a dashboard and story format.
7. The dashboard was embedded into a Flask web application for a clean interactive UI.

---

# Running the Web Application

If you want to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Sham-S08/Electricity-Consumption-Tableau-Analysis.git
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Run the Flask Application

```bash
python app.py
```

---

### 4. Open in Browser

```
http://127.0.0.1:5000
```

The webpage will display the embedded Tableau Public dashboard.

---

# Acknowledgments

Course: **Data Analytics with Tableau – SkillWallet**

Tools used:

- Tableau Public
- MySQL Workbench
- Flask

Dataset inspiration from publicly available electricity consumption datasets.

---

# Author

**Vidushi upadhyay**  
March 2026

Project Repository  
https://github.com/vidushi07upadhyay/Electricity-Consumption-Analysis

---

Made with ⚡ data, visualization, and curiosity for understanding future energy consumption.
