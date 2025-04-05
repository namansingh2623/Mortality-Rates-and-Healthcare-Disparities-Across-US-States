
# 🏥 Health and Mortality Rate Analysis (2023)

## 📌 Overview

This project conducts an in-depth exploratory analysis of the **2023 County Health Ranking data** across U.S. states and counties. The primary objective is to uncover patterns in mortality rates and assess healthcare facility availability, using population and geographic data for greater contextual accuracy.

By integrating population normalization and geospatial visualization, we highlight disparities in healthcare access and outcomes—pinpointing areas where authorities can prioritize improvements to reduce mortality and improve public health standards.

---

# Abstract

This project aims to analyze a comprehensive health dataset for 2023, examining mortality rates in diverse states and counties in the United States. Leveraging advanced data visualization tools like Seaborn, Matplotlib, Holoview, etc, we seek to identify trends in death rates and factors contributing to those deaths. The goal is to elucidate patterns that highlight areas lacking sufficient healthcare facilities, aiding policymakers in directing resources for targeted interventions. This project aims to contribute to evidence-based decision-making for improved public health outcomes.

Our goal is to pay larger emphasis on the availability of medical care facilities in different regions. This information will serve as a valuable resource for policymakers, assisting them in directing resources to areas in urgent need of enhanced medical services. The ultimate goal is to facilitate evidence-based decision-making and contribute to targeted interventions aimed at improving public health outcomes.

- Dataset :  https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation




## 🎯 Goals

- Analyze trends in **premature**, **injury-related**, and **driving-related** deaths.
- Identify regions with limited access to **healthcare facilities**.
- Compare death rates and healthcare status between high and low mortality states.
- Use **data-driven insights** to suggest targeted public health interventions.

---

## 🗂️ Datasets Used

| Dataset | Source |
|--------|--------|
| 2023 County Health Rankings | [countyhealthrankings.org](https://www.countyhealthrankings.org) |
| U.S. Population Data & Shapefiles | [census.gov](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html) |
| California Shapefile | [California Open Data Portal](https://gis.data.ca.gov/datasets/8713ced9b78a4abb97dc130a691a8695) |
| West Virginia Shapefile | [West Virginia GIS](https://wvgis.wvu.edu/data/data.php) |

---

## 📊 Technologies & Tools

- **Python**
- **Pandas, NumPy**
- **Seaborn, Matplotlib, Holoview**
- **Geopandas, Shapely**
- **Jupyter Notebook**

---

## 🔍 Key Features

- 📌 Integrated **population data** to normalize death statistics.
- 🗺️ Used **geospatial shapefiles** to enable accurate state and county-level mapping.
- 📈 Created **interactive and comparative visualizations** to analyze healthcare disparity.
- 🔍 Identified top states by death rates and performed a focused comparison:
  - **West Virginia** (Highest death rate)
  - **California** (Lowest death rate)

---

## ✅ Conclusion

- **West Virginia** showed a significantly higher mortality rate, correlated with fewer healthcare resources and facilities.
- **California** benefited from better infrastructure and access to healthcare, which correlated with its lower death rate.
- The analysis reinforces the **need for targeted improvements** in under-resourced regions to reduce preventable deaths and improve life expectancy.
- This data-driven approach supports public health policy recommendations and resource allocation.

---

## 🧠 Future Work

- Incorporate **real-time hospital and emergency service data**
- Integrate **socioeconomic and insurance coverage statistics**
- Expand analysis to include **mental health and substance abuse** indicators

---

## 🧾 License

This project is for educational purposes only. All external datasets used are publicly available and cited appropriately.

---

## 🙌 Acknowledgements

- [County Health Rankings & Roadmaps](https://www.countyhealthrankings.org)
- [U.S. Census Bureau](https://www.census.gov)
- [California Open Data Portal](https://gis.data.ca.gov)
- [West Virginia GIS Technical Center](https://wvgis.wvu.edu)

---

> 🚀 Let's use data to save lives and drive change in public health!
