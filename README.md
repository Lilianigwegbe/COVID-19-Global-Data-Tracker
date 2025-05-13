# COVID-19 Global Data Tracker

# COVID-19 Data Analysis for Selected Countries

This project analyzes COVID-19 data for Kenya, the USA, and India, sourced from Our World in Data. The analysis includes data loading, cleaning, and visualization, focusing on trends in total cases, deaths, vaccinations, and death rates.

## Project Structure

* `covid19_data_analysis.ipynb`: A Jupyter Notebook containing the Python code for data analysis and visualization.

## Data Source

The data is obtained from the Our World in Data GitHub repository:

* [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv?raw=true)

## Libraries Used

* pandas
* matplotlib.pyplot
* seaborn
* plotly.express

## Analysis Steps

1.  **Data Loading**: The dataset is downloaded and loaded into a pandas DataFrame.
2.  **Data Cleaning**:
    * Data is filtered for Kenya, USA, and India.
    * Dates are converted to datetime format.
    * Missing values in numerical columns are interpolated.
    * Rows with missing dates are removed.
3.  **Exploratory Data Analysis (EDA)**:
    * Line plots are generated to visualize trends in total cases, total deaths, and new cases over time.
    * The COVID-19 death rate (total deaths / total cases) is calculated and plotted.
    * Total vaccination trends are visualized.
    * A choropleth map shows the latest total cases for the selected countries.

## Visualizations

The following visualizations are included in the analysis:

* Total COVID-19 Cases Over Time
* Total COVID-19 Deaths Over Time
* Daily New COVID-19 Cases
* COVID-19 Death Rate (Total Deaths / Total Cases)
* Total COVID-19 Vaccinations Over Time
* Choropleth Map of Total COVID-19 Cases by Country (Latest Data)

## Insights

The analysis provides insights into the progression of the COVID-19 pandemic in Kenya, the USA, and India, highlighting trends in cases, deaths, and vaccinations. The choropleth map provides a snapshot of the latest total cases across the selected countries.
