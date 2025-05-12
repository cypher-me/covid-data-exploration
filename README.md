# COVID-19 Global Data Tracker

A Python-based project designed to track, visualize, and analyze COVID-19 data for **Afghanistan**, with a focus on understanding case trends, vaccination progress, and national impacts through technical visualizations and statistical insights.

## Objectives

* Collect and process COVID-19 datasets specific to Afghanistan.
* Perform data cleaning to handle missing values and ensure consistency.
* Conduct exploratory data analysis to identify key indicators such as case trends, death rates, and vaccination progress.
* Visualize the data using time series plots, correlation matrices, and choropleth maps.
* Generate actionable insights and statistical summaries to support pandemic-related decision-making.

## Tools and Libraries Used

* **Python 3 (via Conda)**
* **Pandas** — Data manipulation and analysis.
* **NumPy** — Numerical computing.
* **Matplotlib** — Data visualization.
* **Plotly (optional for choropleth map)** — Interactive maps and graphs.
* **GeoPandas** — Geospatial analysis.
* **Jupyter Notebook** — Interactive data analysis environment.
* **Visual Studio Code (VSCode)** — Development environment.
* **Ubuntu WSL (Windows Subsystem for Linux)** — Linux-based development shell.

## How to Run/View the Project

1. Clone or download the project repository.
2. Create and activate a conda environment:

   ```bash
   conda create --name covid_tracker python=3.11
   conda activate covid_tracker
   ```
3. Install required libraries:

   ```bash
   conda install pandas numpy matplotlib jupyter
   conda install -c conda-forge plotly geopandas
   ```
4. Download the latest COVID-19 dataset from **Our World in Data**:

   * [OWID COVID-19 Data (CSV)](https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv)
5. Save the dataset as `compact.csv` in the project directory.
6. Launch Jupyter Notebook within VSCode (or from the terminal):

   ```bash
   jupyter notebook
   ```
7. Open and run the notebook file (`main.ipynb`) by executing the cells sequentially.

## Insights and Reflections

* A moderate positive correlation was observed between total cases and vaccination numbers in Afghanistan, highlighting targeted vaccination efforts following rising case counts.
* Data showed distinct waves in case numbers, with vaccination efforts scaling up in response.
* Clear data visualizations effectively communicated temporal changes and healthcare trends.
* This project strengthened technical skills in data preprocessing, advanced visualization, correlation analysis, and efficient workflow management using VSCode on Ubuntu WSL.

---

*Developed as part of a Python Development module project.*
<br>
dev: https://github.com/cypher-me
