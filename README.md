# archeo_monitoring
Geospatial and machine learning-based monitoring of archaeological sites using remote sensing, 3D scanning, and change detection.

# Archaeological Monitoring with Geospatial and Machine Learning Methods

This repository supports a project focused on the long-term monitoring of archaeological sites using remote sensing (Sentinel-2 NDVI/SAVI), 3D LiDAR scanning, and change detection workflows. The goal is to identify and track environmental or anthropogenic disturbances to cultural resources, particularly those affected by low-level helicopter flight training.

## Project Scope

- **Vegetation Monitoring** using NDVI and SAVI indices derived from Sentinel-2 imagery
- **Topographic Analysis** using 1m-resolution LiDAR-derived DEMs to create slope and hillshade layers
- **Change Detection** comparing vegetation and landscape metrics across time
- **Machine Learning** models for future detection of anomalous site changes
- **3D Scan Processing** using Polycam-generated LiDAR models (eventually compared across time)

## Folder Structure
/data/ # All raw and processed spatial data ├── sentinel/ # Sentinel-2 imagery: raw and NDVI/SAVI ├── terrain_data/ # DEMs, slope, and hillshade └── lidar_scans/ # (Placeholder) for Polycam 3D scans

/notebooks/ # Jupyter notebooks for NDVI/SAVI processing, differencing, change detection /models/ # Machine learning models (future) /outputs/ # Analysis outputs for visualizations /utils/ # Python helper functions and scripts /poster/ # Materials for SAA 2025 poster

## Requirements

- Python 3.9+
- QGIS or ArcGIS Pro (optional for preprocessing)
- Libraries: `rasterio`, `numpy`, `matplotlib`, `scikit-learn`, `pyproj`, `pandas`, `geopandas`, `opencv-python`, etc.

See `requirements.txt` for full environment setup.

## Current Status

- NDVI and SAVI completed (March 2024 and 2025)
- DEM slope generation complete
- GitHub repo structure and directory stubs created
- Next steps: change detection notebooks, poster visuals, machine learning pipeline

## Author

Benjamin A. Zandarski II  
Cultural Resource Manager - Fort Carson


---

