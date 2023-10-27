# XAI-tool4GEE

An explainable machine learning tool for land cover mapping and monitoring with GEE

<a target="_blank" href="https://colab.research.google.com/github/GeoAIR-lab/XAI-tool4GEE/blob/main/ml_landcover_app.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Overview

- The explainable machine learning tool is a Jupyter notebook that can be run directly on Google Colaboratory  (Google Colab), which requires no setup on local computers and runs entirely in a browser by remotely connecting with Google's cloud servers. 
- The core functionality of the notebook is built mainly upon two Python packages `geemap` and `ipywidgets`. 
- `geemap` is a Python package for interactive mapping with GEE, which uses the Python API to make computational requests to the Earth Engine servers. Empowered by `ipyleaflet` and `ipywidgets`, `geemap` allows users to interactively analyze and visualize the Earth Engine datasets with Jupyter notebooks. 
- The `scikit-learn` and `shap` packages are also used to calculate the feature importance values. 
- The Colab’s layout widgets are used to organize the classification results and feature importance plots into different display tabs.


## User interface

![](paper/user_interface.JPG "User Interface")

## Workflow for LULC mapping

The typical steps for performing a land cover classification consists of 
- determining the study area, 
- selecting the data source (satellite sensors/bands) and the range of dates to extract the composite image to be classified, 
- preparing sufficient labeled data for supervised classification, 
- selecting a classifier with default or custom parameters, 
- classifying the image, 
- and performing accuracy assessments and some post-processing visualizations. 

![](paper/flowchart_LULC_classification_GEE.jpg "Workflow chart for LULC classification")

## Reference

Chen, H.; Yang, L.; Wu, Q. Enhancing Land Cover Mapping and Monitoring: An Interactive and Explainable Machine Learning Approach Using Google Earth Engine. 
Remote Sens. 2023, 15, 4585. [https://doi.org/10.3390/rs15184585](https://www.mdpi.com/2072-4292/15/18/4585)


# Examples of how-to use

<a href="https://github.com/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/google_sample/example_output_google_samples.ipynb">Example notebook output</a>
<a target="_blank" href="https://colab.research.google.com/github/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/google_sample/example_output_google_samples.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

https://github.com/GeoAIR-lab/XAI-tool4GEE/assets/85247999/290928b6-cf3a-4626-a574-ba4a63e45559

<a href="https://github.com/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/Esri/example_output_sample_esri.ipynb">Example notebook output</a>
<a target="_blank" href="https://colab.research.google.com/github/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/Esri/example_output_sample_esri.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

https://github.com/GeoAIR-lab/XAI-tool4GEE/assets/85247999/a2d804de-4481-431e-a0d3-90b525c57cf6


<a href="https://github.com/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/Dubai/example_output_Dubai.ipynb">Example notebook output</a>
<a target="_blank" href="https://colab.research.google.com/github/GeoAIR-lab/XAI-tool4GEE/blob/main/examples/Dubai/example_output_Dubai.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

https://github.com/GeoAIR-lab/XAI-tool4GEE/assets/85247999/22524d99-d0b0-4796-9fcf-6532ec3706e5

