# GEO5990-final
# README.md

##  Exploring the Relationship Between House Age and Property Prices in Leeds(1995–2020)

###  Last Updated: May 2025


###  Overview
Housing affordability and urban transformation are pressing challenges faced by many UK cities, including Leeds. Understanding the relationship between building age and house prices can provide valuable insights for urban renewal strategies, real estate investment decisions, and housing equity analyses. Older properties may have historical value or structural challenges, while newer properties often reflect recent development trends and planning policies.
This project investigates spatial and temporal variations in house prices across Leeds, UK, using openly available spatial and transactional datasets. It follows a data science process to provide insights that support public good decisions, such as urban planning and improved housing affordability.

###  Objectives

* Understand how house prices have evolved across Leeds from 1995 to 2020.
* Identify spatial inequalities in house prices.
* Highlight relationships between housing types and pricing.
* Communicate insights to stakeholders (e.g. policymakers, homebuyers).

###  Data Sources

•	VOA Property Age Data(voapropertyage.csv)
Source: Valuation Office Agency (VOA). This dataset provides the proportion of residential buildings by construction period within each LSOA. It is used to estimate the distribution of housing age across Leeds.

•	Median House Prices (Median_Prices_Quarterly.csv)
Source: CDRC / HM Land Registry. This dataset contains median house prices by quarter and by LSOA between 1995 Q1 and 2018 Q4, enabling temporal analysis of housing price trends.

•	Average House Prices in 2020–2021(hpssa202103.csv)
Source: CDRC / HM Land Registry..
This dataset provides average house prices by LSOA for Q1 2020 and Q2 2021. Values are averaged over 12 months including the quarter. The dataset is used in the CDRC Mapmaker and is suitable for spatial comparison of recent house prices.

•	Leeds Boundary GeoJSON(Leeds.geojson)
Source: OpenStreetMap (OSM). A GeoJSON file containing the boundaries of LSOAs within the Leeds metropolitan area, required for mapping and spatial analysis.

### What the Code Does
The code in this repository is designed to:

Clean and preprocess raw house price and building age data.

Perform spatial joins and aggregations using geopandas.

Create spatial and non-spatial visualizations to highlight trends in house prices.

Classify housing stock based on building age (e.g., Old House, New House, Unknown).

Generate summary statistics by area and time period.

All results are produced within the notebook geog5990m_final_project_template.ipynb.

### Requirements
To run the project, the following Python packages are required:

pandas

geopandas

matplotlib

seaborn

scikit-learn


### File Structure
File/Folder	Description
geog5990m_final_project_template.ipynb	Main analysis notebook with code and outputs
data/	Folder containing shapefiles and house price data
outputs/	Folder containing final visualizations and results
requirements.txt	Optional file listing Python dependencies for the environment

### How to Run
Clone or download this repository to your local machine.

Create a virtual environment (optional but recommended).

Run pip install -r requirements.txt to install dependencies.

Open the notebook geog5990m_final_project_template.ipynb in Jupyter Notebook or JupyterLab.

Run all cells to reproduce the analysis and visualizations.

### Further Information
For full details on the analysis workflow, visualizations, and interpretation, refer to the main notebook. It includes:

Step-by-step data preprocessing

Classification logic

Mapping and charting

Discussion of patterns and findings
