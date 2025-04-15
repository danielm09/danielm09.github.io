# Geospatial Data Scientist
Machine Learning and Earth Observation enthusiast.  

**Technical Skills:**
- Deep learning, self-supervised learning, masked autoencoders, convolutional neural networks, random forest
- Python: pandas, geopandas, rasterio, gdal, xarray, dask, pytorch, tensorflow, scikit-learn
- Cloud computing (AWS Cloud Practitioner Certificate)
- Docker, CI/CD
- QGIS, ArcGIS, Google Earth Engine (Python & JS APIs)
- Sentinel-2 & Landsat

## Education
- PhD Candidate in Geoinformatics @ Nova IMS, Universidade Nova de Lisboa
- Master's degree in Geographic Information Systems and Science @ Nova IMS, Universidade Nova de Lisboa

## Projects
### NFI-WSL-SSL
<img src="/assets/img/figura_MAE.png" alt="CCD-PluginIcon" width="100%" height="auto">

This project aimed to use data from the Portuguese National Forest Inventory (NFI) for semantic segmentation of land cover on Sentinel-2 images with **convolutional neural networks**. NFI point data were used to create a training sample. NFI-derived sparse labels were used to train a **weakly supervised** semantic segmentation deep learning model based on the ConvNext-V2 architecture. Additionally, a **self-supervised masked autoencoder** model was pretrained and subsequently finetuned using the weakly supervised approach. Results showcased the benefits of the self-supervised pretraining, which improved the overall accuracy over the baseline model.

[![View Project](https://img.shields.io/badge/GitHub-View_Project-blue?logo=GitHub)](https://github.com/danielm09/NFI-WSL-SSL)

### GeoQuery
<img src="/assets/img/diagram_GeoQuery.png" alt="GeoQuery Diagram" width="100%" height="auto">

[:link: Check web app here](http://3.84.27.180:8501/)

This is a **prototype** of a chatbot app designed to answer geospatial questions. It uses an **LLM Agent** powered by **LangChain**, with a set of tools that allow querying reference geospatial datasets, such as a spatial database and geotiff images. Based on a user prompt, the agent decides autonomously which tools and datasets to use in order to answer the question. The app uses the **OpenAI API** but it can also be configured to use local LLMs via **Ollama**. The chat UI is based on **streamlit** and the app is encapsulated in a **docker container**.

[![View Project](https://img.shields.io/badge/GitHub-View_Project-blue?logo=GitHub)](https://github.com/danielm09/GeoQuery)

### GeoRasterRF
<img src="/assets/img/GeoRFIcon.svg" alt="GeoRasterRFIcon" width="100" height="100" />

App containing a graphical user interface to train **Random Forest** models to classify geospatial images. The app also allows users to classify csv data for accuracy assessment. It was developed as a Master's thesis project, which aimed to use Sentinel-2 images and the RF algorithm to classify land cover in Portugal.

[![View Project](https://img.shields.io/badge/GitHub-View_Project-blue?logo=GitHub)](https://github.com/danielm09/GeoRasterRF)

### CCD-Plugin for QGIS (co-developer)
<img src="/assets/img/ccd_plugin.svg" alt="CCD-PluginIcon" width="100" height="100" />

The plugin was developed with the purpose of integrating the **Continuous Change Detection** algorithm to the QGIS environment. It relies on the **Google Earth Engine** platform to retrieve and process Landsat and Sentinel-2 data, providing a fast and simple way to detect changes and explore pixel time series on QGIS. The plugin is publicly available and can be downloaded on QGIS from the official plugins repository.  
  
[![View Project](https://img.shields.io/badge/GitHub-View_Project-blue?logo=GitHub)](https://github.com/SMByC/CCD-Plugin)

### S2Change (contributor)
<img src="/assets/img/S2Change_logo.png" alt="S2Change_logo" width="170" height="auto">

Project developed in collaboration with the General-Directorate of the Territory and the School of Agriculture (University of Lisbon) in Portugal, aiming to map vegetation loss at country scale using the Continuous Change Detection (CCD) algorithm and Sentinel-2 data. Adaptations were made to the **pyccd** implementation of the CCD algorithm in order to allow it to work with **Sentinel-2** images. After an initial stage of development, experimentation and parameter tuning, the project is currently in a phase of tests that include deploying the algorithm countrywide using resources from a **HPC** cluster.

[![View Project](https://img.shields.io/badge/GitHub-View_Project-blue?logo=GitHub)](https://github.com/manuelcampagnolo/S2CHANGE)


## Geospatial data science blog
<img src="/assets/img/medium_icon.png" alt="MediumIcon" width="50" height="50">

[https://medium.com/@moraesd90](https://medium.com/@moraesd90)


## Publications
1. D Moraes, B Barbosa, H Costa, F D Moreira, P Benevides, M Caetano, M Campagnolo. Continuous forest loss monitoring in a dynamic landscape of Central Portugal with Sentinel-2 data. *International Journal of Applied Earth Observation and Geoinformation*. 2024. [https://doi.org/10.1016/j.jag.2024.103913](https://doi.org/10.1016/j.jag.2024.103913)
2. H Costa, P Benevides, F D Moreira, D Moraes, M Caetano. Spatially stratified and multi-stage approach for national land cover mapping based on sentinel-2 data and expert knowledge. *Remote Sensing*. 2022. [https://doi.org/10.3390/rs14081865](https://doi.org/10.3390/rs14081865)
3. D Moraes, M Campagnolo, M Caetano. A Weakly Supervised and Self-Supervised Learning Approach for Semantic Segmentation of Land Cover in Satellite Images with National Forest Inventory Data. *Remote Sensing*. 2025. [https://doi.org/10.3390/rs17040711](https://doi.org/10.3390/rs17040711)
4. D Moraes, M Campagnolo, M Caetano. Training data in satellite image classification for land cover mapping: a review. *European Journal of Remote Sensing*. 2024. [https://doi.org/10.1080/22797254.2024.2341414](https://doi.org/10.1080/22797254.2024.2341414)
5. D Moraes, P Benevides, H Costa, F D Moreira, M Caetano. Influence of sample size in land cover classification accuracy using random forest and sentinel-2 data in Portugal. *IEEE International Geoscience and Remote Sensing Symposium IGARSS*. 2021. [https://doi.org/10.1109/IGARSS47720.2021.9553924](https://doi.org/10.1109/IGARSS47720.2021.9553924)
6.  D Moraes, P Benevides, H Costa, F D Moreira, M Caetano. Assessment of the introduction of spatial stratification and manual training in automatic supervised image classification. *Earth Resources and Environmental Remote Sensing/GIS Applications XII*. 2021. [https://doi.org/10.1117/12.2599740](https://doi.org/10.1117/12.2599740)
7.  D Moraes, P Benevides, H Costa, F D Moreira, M Caetano. Exploring Different Levels of Class Nomenclature in Random Forest Classification of Sentinel-2 Data. *IEEE International Geoscience and Remote Sensing Symposium IGARSS*. 2022. [https://doi.org/10.1109/IGARSS46834.2022.9883798](https://doi.org/10.1109/IGARSS46834.2022.9883798)
8.  D Moraes, P Benevides, H Costa, F D Moreira, M Caetano. Exploring the Use of Classification Uncertainty to Improve Classification Accuracy. *The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences*. 2021. [https://doi.org/10.5194/isprs-archives-XLIII-B3-2021-81-2021](https://doi.org/10.5194/isprs-archives-XLIII-B3-2021-81-2021)
9.  P Benevides, H Costa, F D Moreira, D Moraes, M Caetano. Annual Crop Classification Experiments in Portugal Using Sentinel-2. *IEEE International Geoscience and Remote Sensing Symposium IGARSS*. 2021. [https://doi.org/10.1109/IGARSS47720.2021.9555009](https://doi.org/10.1109/IGARSS47720.2021.9555009)
10.  P Benevides, N Silva, H Costa, F D Moreira, D Moraes, M Castelli, M Caetano. Land cover mapping at national scale with Sentinel-2 and LUCAS: a case study in Portugal. *Remote Sensing for Agriculture, Ecosystems, and Hydrology XXIII*. 2021. [https://doi.org/10.1117/12.2598789](https://doi.org/10.1117/12.2598789)
11.  H Costa, I Machado, F D Moreira, P Benevides, D Moraes, M Caetano. Exploring the Potential of Sentinel-2 Data for Tree Crown Mapping in Oak Agro-Forestry Systems. *IEEE International Geoscience and Remote Sensing Symposium IGARSS*. 2021. [https://doi.org/10.1109/IGARSS47720.2021.9553780](https://doi.org/10.1109/IGARSS47720.2021.9553780)
12.  A Alves, D Moraes, B Barbosa, H Costa, F D Moreira, P Benevides, M Caetano, M Campagnolo. Exploring Spectral Data, Change Detection Information and Trajectories for Land Cover Monitoring over a Fire-Prone Area of Portugal. *GISTAM*. 2023. [https://doi.org/10.5220/0011993100003473](https://doi.org/10.5220/0011993100003473)
   
