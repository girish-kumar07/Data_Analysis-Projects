# Terrorist Attacks Data Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on a dataset
containing global terrorist attacks.\
It includes data loading, cleaning, transformation, and visualization
using **Python**, **Pandas**, **Matplotlib**, and **NumPy**.

## Dataset

The dataset used in this analysis can be downloaded from the link
provided [here](https://drive.google.com/file/d/1M7GNoLhHIE0j4EB3vKvLQtJ2lXoVaJAB/view).

### Key Columns After Cleaning

-   `Country Name`
-   `Country Code`
-   `Attack Year`
-   `No. of Attacks`

## Steps Performed in the Notebook

1.  **Data Loading**
    -   Loaded the CSV file using `pandas.read_csv()`.
2.  **Initial Exploration**
    -   Viewed the data using `head()`, `info()`, and `describe()`.
3.  **Data Cleaning**
    -   Renamed key columns for better readability.
    -   Checked for missing values.
    -   Performed basic transformations.
4.  **Data Visualization**
    -   Plotted trends of terrorist attacks over the years.
    -   Visualized country-wise attack counts.
    -   Used `matplotlib` for visual insights.

## Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib

## How to Run

1.  Install required Python libraries:

    ``` bash
    pip install pandas numpy matplotlib
    ```

2.  Open the Jupyter Notebook:

    ``` bash
    jupyter notebook Terrorist_attacks.ipynb
    ```

3.  Run the cells from top to bottom.

## 🙌 Author

Analysis performed in Jupyter Notebook as part of a data exploration
project.

This project was created to analyze and showcase the Terrorist Attack during the years 2012 to 2023 using data analysis techniques in Python.

Feel free to modify and expand the analysis by adding further statistical tests or visualizations as desired.
