# Unemployment Analysis in India

> An exploratory data analysis of unemployment trends across Indian states and union territories.

This project examines how unemployment changed over time, including the sharp disruption caused by COVID-19. It also compares patterns across regions and between rural and urban areas.

## Overview

The analysis uses the **Unemployment in India** dataset to explore:

- Unemployment rate
- Labour participation rate
- Number of people employed
- Differences between rural and urban areas
- State-wise trends and outliers

The complete analysis is available in a Jupyter Notebook. Pandas is used for data preparation, while Matplotlib and Seaborn are used for visualization.

## Key Insights

| Finding | Observation |
| --- | --- |
| COVID-19 impact | Unemployment spiked sharply during the lockdown period. |
| Urban and rural comparison | Urban areas were more heavily affected than rural areas. |
| Peak period | April 2020 recorded the highest unemployment rate in the dataset. |
| High-unemployment states | Tripura and Haryana showed consistently high unemployment rates. |

See the notebook for the full set of charts and state-by-state breakdowns.

## Repository Structure

```text
Unemployment-Analysis-India/
├── Unemployment_Analysis_India.ipynb   # Main analysis notebook
├── Unemployment in India.csv           # Dataset
└── README.md
```

## Dataset

The file `Unemployment in India.csv` contains region-level records with the following fields:

| Column | Description |
| --- | --- |
| `Region` | State or union territory |
| `Date` | Date of the observation |
| `Frequency` | Reporting frequency, such as Monthly |
| `Estimated Unemployment Rate (%)` | Percentage of people unemployed |
| `Estimated Employed` | Number of people employed |
| `Estimated Labour Participation Rate (%)` | Percentage of the working-age population in the labour force |
| `Area` | Rural or Urban |

## Tech Stack

- **Python 3**
- **Pandas** for data cleaning and manipulation
- **NumPy** for numerical operations
- **Matplotlib / Seaborn** for data visualization
- **Jupyter Notebook** for the analysis environment

## Getting Started

### Prerequisites

- Python 3.8 or later
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/NisthaJain698/Unemployment-Analysis-India.git
cd Unemployment-Analysis-India
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Notebook

```bash
jupyter notebook Unemployment_Analysis_India.ipynb
```

Run the cells in order. The notebook loads `Unemployment in India.csv`, cleans the data, and generates the visualizations referenced above.

## Project Type

Exploratory Data Analysis (EDA)

## Future Improvements

- Add a `requirements.txt` file for one-command environment setup
- Break the notebook into reusable scripts and functions
- Add interactive visualizations with Plotly
- Include a short write-up or dashboard summarizing the findings

## Author

**Nistha Jain** - [GitHub](https://github.com/NisthaJain698)

## License
This project is open-source and licensed under the MIT License. You are free to use, modify, and distribute the project in accordance with the terms of the license.

For full details, please refer to the LICENSE file included in this repository.
