
# Advanced Visual Analytics - Mandatory Assignment

This repository contains a Jupyter Notebook for an advanced visual analytics assignment. The tasks involve analyzing different datasets to uncover insights and patterns. The assignment covers three main tasks, each focusing on different data sources and analytical techniques.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Setup and Installation](#setup-and-installation)
4. [Tasks Overview](#tasks-overview)
   - [Task 1: Travel Data Analysis](#task-1-travel-data-analysis)
   - [Task 2: Tuberculosis Data Analysis](#task-2-tuberculosis-data-analysis)
   - [Task 3: Weather Data Analysis](#task-3-weather-data-analysis)
5. [Usage](#usage)
6. [Results](#results)
7. [Dependencies](#dependencies)

## Project Overview

The assignment consists of analyzing datasets related to:
- Travel patterns in the USA (automobile, train, and air travel).
- Tuberculosis cases reported by the World Health Organization (WHO).
- Weather patterns over a specified period.

The analyses aim to highlight trends, detect significant events' impacts (e.g., September 11, 2001), and uncover insights for specific regions and periods.

## Data Sources

The project uses the following datasets:
1. **Travel Data**: Monthly passenger movement data for the USA from January 1990 to April 2004.
2. **WHO Tuberculosis Data**: Tuberculosis cases data before and after the year 2000, covering various countries.
3. **Weather Data**: Temperature measurements for specific days of the month.

## Setup and Installation

To run the notebook locally:
1. Clone this repository.
2. Ensure you have the following Python libraries installed:
   - `pandas`
   - `numpy`
   - `seaborn`
   - `matplotlib`
   - `statsmodels`
3. Place the required data files in the specified directory or update the file paths in the notebook accordingly.

## Tasks Overview

### Task 1: Travel Data Analysis
- **Objective**: Analyze monthly travel data (automobile, train, and air) in the USA.
- **Steps**:
  1. Load and merge the datasets.
  2. Plot time series graphs to compare travel patterns across different modes.
  3. Examine the impact of significant events, such as the September 11 attacks.

### Task 2: Tuberculosis Data Analysis
- **Objective**: Analyze global Tuberculosis data, focusing on Afghanistan, Norway, and India.
- **Steps**:
  1. Merge datasets for periods before and after 2000.
  2. Convert the data into a tidy format.
  3. Generate reports and visualize trends.

### Task 3: Weather Data Analysis
- **Objective**: Examine temperature data to identify monthly trends.
- **Steps**:
  1. Tidy up the temperature data.
  2. Plot temperature trends and identify patterns.

## Usage

To run the notebook:
1. Open the Jupyter Notebook file (`Visual-analytics-Mandatory-assignment.ipynb`).
2. Execute the cells sequentially.
3. Modify the file paths as needed to point to the location of the datasets on your system.

## Results

The notebook includes visualizations and statistical analyses for each task. Findings for travel patterns, Tuberculosis trends, and weather data patterns are documented in the respective sections.

## Dependencies

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `statsmodels`

Install dependencies via pip if needed:
```bash
pip install pandas numpy seaborn matplotlib statsmodels
```
