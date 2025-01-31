# 🏙️ Spatial Analysis of Distance to Transit Stops  

This repository contains scripts and data files for analyzing **the average distance to transit stops** (bus and metro) in selected parishes. The project utilizes **Python, GeoPandas, Folium, and OSMnx** for spatial analysis and visualization.  

## 📌 Project Overview  

The goal of this project is to:  
- **Analyze building accessibility** to nearby transit stops.  
- **Compute average distances** from buildings to metro and bus stops using a street network.  
- **Generate interactive maps** with Folium for better visualization.  
- **Provide insights for urban planning and transport accessibility.**  

## 📂 Files in this Repository  

| File | Description |
|------|------------|
| `Distance-transit-stops.ipynb` | Jupyter Notebook calculating the **average distance** from buildings to transit stops (bus and metro). |
| `edificios.csv` | CSV file containing building locations with WKT geometries. |
| `freguesia.csv` | CSV file defining the boundaries of the selected parishes. |
| `metro.csv` | CSV file with metro stop locations. |
| `stcp.csv` | CSV file with STCP (bus) stop locations. |

## 🛠️ Setup & Dependencies  

To run the Jupyter notebooks, install the necessary dependencies:  

```bash
pip install pandas geopandas osmnx folium networkx shapely joblib matplotlib numpy
