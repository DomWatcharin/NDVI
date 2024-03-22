# NDVI (Normalized Difference Vegetation Index) Analysis using Landsat 8

### 1. Python Environment Setup and Libraries Installation

Ensure that the required Python libraries are installed by running the following command:

```bash
pip install rasterio geopandas numpy matplotlib earthengine-api pyproj
```

### 2. Downloading Landsat Scenes with Google Earth Engine

This script downloads Landsat scenes using Google Earth Engine, filters them based on specified criteria, and exports the NIR and Red bands to Google Drive.

### 3. Download Landsat 8 Images from Google Drive to Local Path

This script downloads Landsat scenes from Google Drive and saves them to the local path.

**Output:**

- Merged NIR band saved as: `landsat_downloads/nir_band_merged.tif`
- Merged Red band saved as: `landsat_downloads/red_band_merged.tif`

### 4. Merging NIR and Red Bands from Two Scenes

This script merges NIR and Red bands from two Landsat scenes into single GeoTIFF files.

**Output:**

- Merged NIR band saved as: `landsat_downloads/nir_band_merged.tif`
- Merged Red band saved as: `landsat_downloads/red_band_merged.tif`

### 5. Clipping NDVI with Bangkok Boundary and Export to GeoTIFF

#### Clip NDVI with Bangkok Boundary

This script clips the NDVI raster with the boundary of Bangkok and exports the clipped NDVI to a GeoTIFF file.

**Output:**

- Clipped NDVI saved as: `ndvi/ndvi_clip.tif`

#### Plot NDVI and Export Plot to PNG

This script plots the clipped NDVI and exports the plot to a PNG file.

**Output:**

- NDVI plot saved as: `ndvi/ndvi_plot.png`

![Clipped NDVI](https://github.com/DomWatcharin/NDVI/blob/1a2a4da85c7cc3ac64e732d08bb2253ac5e55120/ndvi/ndvi_clip.png)

![NDVI Plot](https://github.com/DomWatcharin/NDVI/blob/206b39a5792188ae754a2b559821be785fe2044d/ndvi/ndvi_plot.png)
