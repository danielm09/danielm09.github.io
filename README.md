# Data Scientist
Technical Skills: pandas, geopandas, rasterio, gdal, xarray, dask, pytorch, tensorflow, scikit-learn

## Education
- PhD Candidate in Geoinformatics | Nova IMS, Universidade Nova de Lisboa
- Master's degree in Geographic Information Systems and Science | Nova IMS, Universidade Nova de Lisboa

## Projects
### GeoRasterRF
App containing a graphical user interface to train Random Forest models to classify geospatial images. The app also allows users to classify csv data for accuracy assessment. It was developed for our Master's thesis, which aimed to use Sentinel-2 images and the RF algorithm to classify land cover in Portugal.  
![GeoRasterRFIcon](/assets/img/GeoRFIcon.svg)
[Link to repo](https://github.com/danielm09/GeoRasterRF)
### CCD-Plugin for QGIS (co-developer)
The plugin was developed with the purpose of integrating the Continuous Change Detection algorithm to the QGIS environment. It relies on the Google Earth Engine platform to retrieve and process Landsat and Sentinel-2 data, providing a fast and simple way to detect changes and explore a pixel time series in QGIS. The plugin is publicly available and can be downloaded on QGIS from the official plugins repository.    
![CCD-PluginIcon](/assets/img/ccd_plugin.svg)
[Link to repo](https://github.com/SMByC/CCD-Plugin)
### S2Change (contributor)
Project developed in collaboration with the General-Directorate of the Territory and the School of Agriculture (University of Lisbon) in Portugal, aiming to map vegetation loss at country scale using the Continuous Change Detection (CCD) algorithm and Sentinel-2 data. Adaptations were made to the pyccd implementation of the CCD algorithm in order to allow it to work with Sentinel-2 images. After an initial stage of development, experimentation and parameter tuning, the project is currently in a phase of tests that include deploying the algorithm countrywide using resources from a HPC cluster.  
[Link to repo](https://github.com/manuelcampagnolo/S2CHANGE)
### IFN-WSL-SSL (migration to GitHub in progress)
This project aimed to use data from the Portuguese National Forest Inventory (NFI) for semantic segmentation of land cover on Sentinel-2 images with convolutional neural networks. NFI point data were used to create a training sample. NFI-derived sparse labels were used to train a weakly supervised semantic segmentation deep learning model based on the ConvNext-V2 architecture. Additionally, a self-supervised model was pretrained and subsequently finetuned using the weakly supervised approach. Results showcased the benefits of the self-supervised pretraining, which improved the overall accuracy over the baseline model.  
[Link to repo](https://github.com/danielm09/IFN_WSL_Deploy)
