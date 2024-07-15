

# AtliQ Hotels Analysis

This Jupyter Notebook contains an analysis of data related to AtliQ Hotels. The notebook includes the following main sections:

## Table of Contents
1. [Introduction](#introduction)
2. [Importing Libraries](#importing-libraries)
3. [Loading Data](#loading-data)
4. [Data Exploration](#data-exploration)
5. [Data Analysis](#data-analysis)
6. [Visualizations](#visualizations)
7. [Conclusions](#conclusions)
8. [Usage](#usage)
9. [Requirements](#requirements)

## Introduction
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category.

## Importing Libraries
The notebook starts by importing the necessary Python libraries for data manipulation, analysis, and visualization. The primary libraries used are:
- `numpy`
- `pandas`
- `matplotlib`

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

## Loading Data
This section involves loading the various datasets required for the analysis. The datasets are imported from CSV files located in a specified directory. The files include:
- `dim_date.csv`
- `dim_hotels.csv`
- `dim_rooms.csv`
- `fact_aggregated_bookings.csv`
- `fact_bookings.csv`

```python
filepath1 = '/content/drive/MyDrive/Hospitality/dim_date.csv'
filepath2 = '/content/drive/MyDrive/Hospitality/dim_hotels.csv'
filepath3 = '/content/drive/MyDrive/Hospitality/dim_rooms.csv'
filepath4 = '/content/drive/MyDrive/Hospitality/fact_aggregated_bookings.csv'
filepath5 = '/content/drive/MyDrive/Hospitality/fact_bookings.csv'

dim_date = pd.read_csv(filepath1)
dim_hotels = pd.read_csv(filepath2)
dim_rooms = pd.read_csv(filepath3)
fact_aggregate = pd.read_csv(filepath4)
fact_bookings = pd.read_csv(filepath5)
```

## Data Exploration
In this section, the notebook explores the imported datasets to understand their structure, content, and key characteristics. This typically includes displaying the first few rows of each dataframe, checking for missing values, and examining data types.

```python
dim_date.head()
dim_hotels.head()
dim_rooms.head()
fact_aggregate.head()
fact_bookings.head()
```

## Data Analysis
The core of the notebook involves various data analysis tasks. These tasks might include:
- Aggregating and summarizing data
- Identifying trends and patterns
- Performing statistical analysis

## Visualizations
To enhance the understanding of the data, the notebook includes visualizations such as:
- Line charts
- Bar charts
- Pie charts

These visualizations help in presenting insights in a more comprehensible manner.

## Conclusions
The notebook concludes with a summary of the findings from the analysis. It might also include recommendations or next steps based on the insights gained.

## Usage
To use this notebook:
1. Ensure you have Python and Jupyter Notebook installed.
2. Clone the repository and navigate to the directory containing the notebook.
3. Open the notebook using Jupyter Notebook.
4. Run the cells sequentially to execute the analysis.

## Requirements
- Python 3.x
- Jupyter Notebook
- numpy
- pandas
- matplotlib

Install the required libraries using:
```bash
pip install numpy pandas matplotlib
```





