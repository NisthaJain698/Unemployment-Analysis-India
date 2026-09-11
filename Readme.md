📊 Unemployment Analysis in India

Exploratory data analysis of unemployment trends across Indian states, built with Python. The project examines how unemployment evolved over time — including the sharp disruption caused by COVID-19 — and compares patterns across regions, and between rural and urban areas.

Overview

This project uses the Unemployment in India dataset to explore how the unemployment rate, labour participation rate, and number of people employed changed across Indian states and union territories. The analysis is done in a single Jupyter notebook using Pandas for data wrangling and Matplotlib/Seaborn for visualization.

Objectives
Analyze overall unemployment trends over time
Study the impact of COVID-19 on employment
Compare unemployment between rural and urban areas
Identify state-wise patterns and outliers
Surface insights that could inform policy discussions
Key Insights
Unemployment spiked sharply during the COVID-19 lockdown period
Urban areas were more heavily affected than rural areas
April 2020 recorded the peak unemployment rate in the dataset
States like Tripura and Haryana showed consistently high unemployment rates

(See the notebook for the full set of charts and state-by-state breakdowns.)

Repository Structure
Unemployment-Analysis-India/
├── Unemployment_Analysis_India.ipynb   # Main analysis notebook
├── Unemployment in India.csv           # Dataset
└── README.md
Dataset

The dataset (Unemployment in India.csv) contains region-level records with fields such as:

Column	Description
Region	State / union territory
Date	Date of the observation
Frequency	Reporting frequency (Monthly)
Estimated Unemployment Rate (%)	% of people unemployed
Estimated Employed	Number of people employed
Estimated Labour Participation Rate (%)	% of working-age population in the labour force
Area	Rural / Urban


Tech Stack
Python 3
Pandas – data cleaning and manipulation
NumPy – numerical operations
Matplotlib / Seaborn – data visualization
Jupyter Notebook – analysis environment
Getting Started
Prerequisites
Python 3.8+
Jupyter Notebook or JupyterLab
Installation
bash
git clone https://github.com/NisthaJain698/Unemployment-Analysis-India.git
cd Unemployment-Analysis-India
pip install pandas numpy matplotlib seaborn jupyter
Run the Notebook
bash
jupyter notebook Unemployment_Analysis_India.ipynb

Run the cells in order — the notebook loads Unemployment in India.csv, cleans the data, and generates the visualizations referenced above.

Project Type

Exploratory Data Analysis (EDA)

Future Improvements
Add a requirements.txt for one-command environment setup
Break the notebook into reusable scripts/functions
Add interactive visualizations (e.g., Plotly) for state comparisons
Include a short write-up or dashboard summarizing findings
Author

Nistha Jain — GitHub

License
