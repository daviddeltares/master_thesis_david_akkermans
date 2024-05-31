# Master-Thesis-David-Akkermans

This repository contains the code and resources used for processing and analyzing Automatic Identification System (AIS) data within my Master Thesis project, focusing on the impact of extreme low discharge events on vessel movements in the Waal River near Nijmegen.

### Project Overview

This research investigates how vessel behavior changes in the Waal bottleneck during periods of drought, utilizing AIS data to examine spatial distribution, speed, and trajectory patterns. The findings have important implications for waterway management, infrastructure planning, and navigation safety in the face of increasing drought risks.

### Repository Contents

Notebooks: Jupyter notebooks containing the Python code for data preprocessing, analysis, and visualization.
QGIS Project: The QGIS project file used for creating the bathymetric map and visualizing vessel trajectories.
Data: This folder contains the additional data used in the analysis, including bathymetry and river discharge data. Please note that the raw AIS data is not included due to its confidential nature.

### Requirements

Planetary Computer: The notebooks were run on the Microsoft Planetary Computer Hub, which provides access to scalable computing resources and pre-installed libraries.

QGIS: The QGIS project file can be opened and explored in QGIS software.

### Code Order/Placement
First, the raw AIS data is processed in the traj_splitting notebook. Then this enhanced and preprocessed dataset is used to conduct the EDA in the notebooks lateral_distributions and visualisations_and_bumptesting. In these two notebooks the data is also further processed to be able to conduct the comfirmatory analyses. 

### Disclaimer

The raw AIS data used in this research is not publicly available due to its confidential nature and requires a SAS token from Rijkswaterstaat for access. However, the processed data and results presented in this repository can be used to understand the research findings and methodology.
