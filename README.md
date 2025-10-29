# Global Temperature Analysis
### Abinash Patti

## Project Overview
Exploratory data analysis (EDA) of global temperature trends using the [Berkeley Earth Climate Dataset](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data).

This project investigates how temperatures have changed over time, both globally and by country. It identifies outliers, visualizes long-term warming trends, and the shortcomings of this dataset. The analysis uses historical temperature data from 1743 to 2013, showcasing data cleaning, aggregation, analysis, and visualization techniques in Python.

## Goals
- Clean and explore historical temperature data
- Visualize long-term climate trends
- Identify anomolies and outliers
- Compare country-level trends and identify regions that defy global warming
- Check for inaccuracies and shortcomings in datset

## Visualizations and Analysis

All findings and charts are available in the following Jupyter Notebooks:

- [01_Exploration.ipynb](notebooks/01_exploration.ipynb)
- [02_Visualization.ipynb](notebooks/02_visualization.ipynb)
  - The visualization notebook shows key climate trends such as global temperature increase, extreme temperatures, temperature ranges for each country, and countries that defy the overall trend.

## Key Findings

**Global Temperature Trends**

- The global average temperature has risen significantly since the late 19th century, confirming that global warming is occuring.
- Early data (the first ~100 years in the dataset) is quite inconsistent and biased towards Europe and North America; this results in inaccurate data as it isn't truly global.
- After 1880, the data becomes more consistent, showing a linear upwards trend in global average temperature.

**Countries Defying the Trend**
- A handful of countries show a slight cooling trend in the dataset, indicating that they defy global warming.
- Upon further review using visual tools, this seems to be an issue with some inaccuracies in the dataset.

## Installation

**Requirements**

Install all dependencies by running:

```bash
cd globaltemperatureanalysis
pip insall -r requirements.txt
```

**Dataset**

Download the dataset from [Kaggle](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data/data)

Add the CSVs to the `data/` folder.

**Running the program**

Run the Jupyter notebooks in order:
- `01_Exploration.ipynb`
- `02_Visualization.ipynb`

## Tools & Technologies
- Python
- Jupyter Notebooks for workflow and building reports
- Kaggle for dataset
- Pandas for data cleaning and manipulation
- Matplotlib for data visualization

## Future Improvements
- Add time-series smoothing to better visualize changes by decade.
- Incorporate more datasets (carbon levels, sea levels, etc).
- Create an interactive dashboard using Streamlit.
