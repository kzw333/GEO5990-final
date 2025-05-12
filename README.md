# GEO5990-final
# README.md

##  Exploring the Relationship Between House Age and Property Prices in Leeds(1995–2020)

###  Last Updated: May 2025

---

###  Overview

This project investigates spatial and temporal variations in house prices across Leeds, UK, using openly available spatial and transactional datasets. It follows a data science process to provide insights that support public good decisions, such as urban planning and improved housing affordability.

---

###  Objectives

* Understand how house prices have evolved across Leeds from 1995 to 2020.
* Identify spatial inequalities in house prices.
* Highlight relationships between housing types and pricing.
* Communicate insights to stakeholders (e.g. policymakers, homebuyers).

---

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


###  How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/leeds-house-price-insight.git
cd leeds-house-price-insight
```

2. Open the Jupyter notebook:

```bash
jupyter notebook leeds_analysis.ipynb
```

3. Ensure you have the required Python libraries:

```bash
pip install geopandas matplotlib pandas
```



###  Acknowledgements

* UK Land Registry
* Office for National Statistics (ONS)
* University of Leeds GIS & Data Science Module
