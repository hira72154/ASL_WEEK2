# ASL_WEEK2 — Titanic Data Analysis

## Project Overview

This project performs data wrangling, data cleaning, exploratory data analysis (EDA), and visualization on the Titanic dataset using Python. The raw dataset was unwrangled — it contained missing values and required cleaning before any meaningful analysis could be performed.

## Dataset

- **Name:** Titanic Dataset (`titanic.csv`)
- **Source:** [Titanic Dataset (CSV)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Size:** 891 rows × 12 columns
- **Description:** Contains passenger-level data from the Titanic, including age, gender, passenger class, fare, port of embarkation, and survival status.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

### Installation

Install all required libraries using `pip` and the provided `requirements.txt`:

```bash
pip install -r requirements.txt
```

`requirements.txt`:

```
pandas
numpy
matplotlib
jupyter
```

Alternatively, install each library individually from the terminal:

```bash
pip install pandas numpy matplotlib jupyter
```

Then launch the notebook with:

```bash
jupyter notebook
```

> **Note on setup:** Setting up the environment (virtual environment, correct Python interpreter, and library versions) was one of the more difficult parts of this project — several package and path errors came up along the way. AI assistance was used to debug these setup issues and get the environment running correctly.

## Project Structure

```
ASL_WEEK2/
├── data/
│   └── titanic.csv
├── notebooks/
│   └── eda.ipynb
└── README.md
```

## Tasks Performed

- Loaded the dataset
- Inspected the data (shape, columns, data types)
- Cleaned missing values (Age, Cabin, Embarked)
- Checked for duplicate records
- Performed GroupBy analysis (Age and Fare by Passenger Class, Survival Rate by Gender)
- Created visualizations

## Visualizations

- Histogram
- Bar Chart
- Pie Chart
- Line Graph
- Box Plot

## Key Findings

- **Gender and survival:** Female passengers had a much higher survival rate (~74%) than male passengers (~19%), reflecting the "women and children first" evacuation priority.
- **Class and fare:** First Class passengers paid significantly higher average fares (~$84) than Second (~$21) and Third Class (~$14) passengers, and were also older on average.
- **Passenger distribution:** Most passengers traveled in Third Class (55.1%), and overall, more passengers died (61.6%) than survived (38.4%).

## Author

Hira Nadeem
