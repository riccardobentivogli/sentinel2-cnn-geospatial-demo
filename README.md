# Sentinel-2 Patch CNN Demo

This repository demonstrates a **geospatial machine learning workflow** using Sentinel-2 satellite data and convolutional neural networks.

The project showcases how multispectral satellite data can be processed and used for environmental prediction tasks such as chlorophyll-a estimation.

## Workflow

1. Download Sentinel-2 L2A imagery
2. Resample bands and subset geographic region
3. Extract 5x5 pixel patches around point locations
4. Train a CNN using spectral reflectance patches

## Repository structure
sentinel2-patch-cnn-demo
│
├── configs/ # configuration files
├── data/ # demo and placeholder datasets
├── notebooks/ # interactive notebooks for workflow demonstration
├── src/ # main python scripts
├── outputs/ # generated figures and trained models
├── docs/ # documentation
│
├── README.md
├── requirements.txt
├── .gitignore



## Data

This repository includes only synthetic or demonstration datasets to illustrate the workflow.

Original in situ chlorophyll-a measurements and exact sampling coordinates used in research applications are not distributed due to data-sharing constraints.

## Installation

git clone https://github.com/YOURUSERNAME/sentinel2-patch-cnn-demo.git

pip install -r requirements.txt

## Example workflow

python src/download_s2.py  
python src/preprocess_s2.py  
python src/extract_patches.py  
python src/train.py  

## Tech stack

Python  
GeoPandas  
Rasterio  
TensorFlow  
Scikit-learn  

## Author

Riccardo Bentivogli
