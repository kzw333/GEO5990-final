# GEO5990-final
# README.md

## 🌍 Leeds House Price Insight Project

### 📅 Last Updated: May 2025

---

### 🔎 Overview

This project investigates spatial and temporal variations in house prices across Leeds, UK, using openly available spatial and transactional datasets. It follows a data science process to provide insights that support public good decisions, such as urban planning and improved housing affordability.

---

### 📈 Objectives

* Understand how house prices have evolved across Leeds from 1995 to 2020.
* Identify spatial inequalities in house prices.
* Highlight relationships between housing types and pricing.
* Communicate insights to stakeholders (e.g. policymakers, homebuyers).

---

### 📄 Data Sources

1. **UK Land Registry Price Paid Data**

   * Source: [https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads)
   * Data: Residential property transactions in England and Wales
   * Licence: Open Government Licence v3.0

2. **ONS LSOA Boundaries (Leeds)**

   * Source: [https://geoportal.statistics.gov.uk](https://geoportal.statistics.gov.uk)
   * Data: Lower Layer Super Output Area (LSOA) shapefiles for Leeds
   * Licence: Open Government Licence

---

### 🔢 Key Files

| File                   | Description                                                    |
| ---------------------- | -------------------------------------------------------------- |
| `leeds_analysis.ipynb` | Main analysis notebook (see structure below)                   |
| `data/`                | Folder containing shapefiles and house price data              |
| `outputs/`             | Folder containing final spatial and non-spatial visualisations |
| `requirements.txt`     | Optional file listing Python dependencies                      |

---

### 📊 Final Outputs

#### 🌍 Spatial Visualisation (for policymakers)

* **Title:** Average House Prices in Leeds, 2020
* **Insight:** Identifies areas where affordability is low.
* **Design:** Color-coded map using a choropleth style.

#### 📉 Non-Spatial Visualisation (for the public/homebuyers)

* **Title:** Average House Prices by Type (2020)
* **Insight:** Shows pricing differences by house type (e.g. detached vs flat).
* **Design:** Clear, readable bar chart with colour differentiation.

---

### 🚀 How to Run

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

---

### 📚 License

This project uses open datasets licensed under the Open Government Licence. All code is shared under the MIT License.

---

### 📍 Acknowledgements

* UK Land Registry
* Office for National Statistics (ONS)
* University of Leeds GIS & Data Science Module
