# 🌍 Spatial Data & Data Sources  

Spatial data is the foundation of Geographic Information Systems (GIS) and Remote Sensing. It comes in different formats and can be sourced from various platforms. This document provides an overview of spatial data types, sources, and how they are used in geospatial applications.

---

## 📌 Types of Spatial Data
| Data Type | Description | Common Formats |
| :--- | :--- | :--- |
| **Vector Data** | Points, Lines, and Polygons (e.g., roads, buildings). | .shp, .geojson, .gpkg, .kml |
| **Raster Data** | Gridded pixels (e.g., satellite imagery, DEMs, temperature). | .tiff, .jp2, .hdf, .img |
| **Tabular Data** | Non-spatial attribute info linked to geographic features. | .csv, .xlsx, .dbf |
| **Metadata** | Descriptive "data about data" (ancillary info). | .xml, .txt, .json |
## 💡 Tips for Data Sourcing
When choosing a data source for your GIS project, keep these factors in mind:
*   **Scale**: Is the data detail appropriate for your study area (e.g., global vs. local)?
*   **Temporal Resolution**: How often is the data updated? Is it recent enough for your needs?
*   **Coordinate System**: Always check the CRS (Coordinate Reference System) to ensure it aligns with your existing layers.
*   **Format Compatibility**: Ensure your software (QGIS, ArcGIS, Python) can natively read the format (e.g., Shapefile, GeoJSON, GeoTIFF).

---

## 🌐 Open Spatial Data Sources

### 🛰️ Satellite Imagery
| Provider | Focus Area | Link |
| :--- | :--- | :--- |
| **NASA Earthdata** | Comprehensive planetary data, climate, and imagery. | [earthdata.nasa.gov](https://earthdata.nasa.gov) |
| **USGS Earth Explorer** | Landsat, aerial imagery, and global DEMs. | [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov) |
| **Copernicus Hub** | European Sentinel-1, -2, -3, and -5P mission data. | [scihub.copernicus.eu](https://scihub.copernicus.eu) |
| **WEkEO** | Cloud computing platform with access to all Copernicus data (Sentinel & Hubs) in one place. | [wekeo.copernicus.eu](https://wekeo.copernicus.eu/) |

### 🗺️ Administrative & OpenStreetMap (OSM) Data
| Provider | Focus Area | Link |
| :--- | :--- | :--- |
| **OpenStreetMap** | Community-driven global vector base mapping. | [openstreetmap.org](https://www.openstreetmap.org) |
| **Natural Earth** | Free vector and raster map data (1:10m, 1:50m). | [naturalearthdata.com](https://www.naturalearthdata.com) |
| **HDX** | Humanitarian datasets, boundaries, and crisis info. | [data.humdata.org](https://data.humdata.org) |

### 🌱 Environmental & Climate Data
| Provider | Focus Area | Link |
| :--- | :--- | :--- |
| **WorldClim** | Global climate surfaces, bio-climatic variables. | [worldclim.org](https://www.worldclim.org) |
| **NASA POWER** | Solar and meteorological data for energy and agri. | [power.larc.nasa.gov](https://power.larc.nasa.gov) |
| **Global Forest Watch** | Real-time forest monitoring and land-use metrics. | [globalforestwatch.org](https://www.globalforestwatch.org) |

### 🚀 Elevation & Terrain Data
| Provider | Focus Area | Link |
| :--- | :--- | :--- |
| **NASA SRTM** | 30m resolution global elevation (3-arc second). | [srtm.csi.cgiar.org](https://srtm.csi.cgiar.org) |
| **ALOS PALSAR** | High-res global 12.5m radiometrically corrected DEM. | [search.asf.alaska.edu](https://search.asf.alaska.edu) |
| **GEE Data Catalog** | Massive multi-petabyte analysis-ready data catalog. | [Earth Engine datasets](https://developers.google.com/earth-engine/datasets) |

### 🤖 Machine Learning Benchmark Datasets
| Provider | Focus Area | Link |
| :--- | :--- | :--- |
| **Pangeo** | Benchmark datasets for Earth System ML. | [mldata.pangeo.io](https://mldata.pangeo.io/index.html) |
| **Kaggle** | Massive repository of open ML datasets. | [kaggle.com/datasets](https://www.kaggle.com/datasets) |

---
## 📌 Contributing  
Feel free to suggest additional topics or share relevant data sources. If you have useful datasets, tools, or research papers, consider contributing to this repository!
