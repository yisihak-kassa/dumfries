# Dumfries Hydrogeological Model

This repository contains a Jupyter notebook of **hydrogeological modeling** of the **Dumfries** groundwater basin located in Southern Scotland developed during the class "Groundwater Flow Modelling" at the University of Strathclyde. The notebook includes:

- Groundwater modeling with **MODFLOW** using **Flopy**
- Flowpath computation with **MODPATH**
- Solute transport modelling with **MT3DMS**
- GIS data handling with **GeoPandas** and **Rasterio**
- Basic **matplotlib plotting**

## Installation & Dependencies

The GIS files are located in the "GIS" folder.
MODFLOW, MODPATH and MT3DMS are included in their respective directories.

Required python packages:

```
flopy geopandas rasterio matplotlib numpy
```

## Usage

Simply open `dumfries.ipynb` in Jupyter Notebook and execute the cells to preprocess GIS data and run the simulations.
