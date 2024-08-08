# 🛰️ Dataset-Information

This dataset contains satellite images processed into 800x800 pixel segments. The dataset aims to aid in the development and evaluation of ship detection algorithms using synthetic aperture radar (SAR) imagery and has been verified by SAR experts.

You can find the steps for creating a database using the GDAL library in this [GitHub repository](https://github.com/kazimhanbay/SAR-Database-Creation-with-GDAL).


## 📊 Dataset Version 1 | Description

The first version of the dataset is divided into two main categories:

1. **🚢 Ship**: Contains images with various types of ships and includes 10,0021 images.
2. **🌊 Sea**: Contains images of the sea without ships and includes 13,656 images.

### Example
<img src="https://github.com/user-attachments/assets/35bd9d26-ff40-493e-a556-dfefe597a971" alt="Ship and Sea Image Dataset" width="600">

### 📥 Download
- You can download the dataset from [DatasetV1](https://drive.google.com/drive/folders/13v51flw7uivqM5h30_bQFW0PUyTV7zsF?usp=drive_link).
- You can download the dataset from [DatasetV1 with Real-ESRGAN](https://drive.google.com/drive/folders/15gGSvJbJ-3TBF_fh-HVGko5W9HPAqIZs?usp=drive_link).


## Note: 
The two categories consist of a total of 23,677 (13,656 Sea - 10,0021 Ship) images.

## 📊 Dataset Version 2 | Description

The second version of the dataset has been processed using real-esrgan and contains categories such as land/ship/sea and ship.

The second version of the dataset is divided into two main categories:

1. **🚢 Ship**: Contains images with various types of ships and includes 7945 images.
2. **🌊🚢🏝️ Sea/Ship/Land**: Contains images of the mix (sea, ship, land) and includes 2821 images.

### Example
<img src="https://github.com/user-attachments/assets/6e934c9b-fe39-41c5-ab2f-231529682ced" alt="Version 2 Dataset" width="600">

### 📥 Download
You can download the dataset from [DatasetV2](https://drive.google.com/drive/folders/1uQnPQgt_6ruTGXE-U9jYuxEvraHLb0f8?usp=drive_link).

## Note:  
The two categories consist of a total of 10,766 (2821 Land/Sea/Ship - 7945 Ship) images.

## 🖼️ Image Specifications

- **Resolution**: The data were acquired in IW mode.
- **Size**: Each image segment is 800x800 pixels.
- **Polarization Types**: The dataset images are provided with VV polarizations.

## 📝 Annotations

The verification process was carried out entirely by SAR experts without relying on AIS data or Google Earth.

## 📚 Usage

This dataset can be used for training and testing machine learning models for tasks such as:

- 🚢 Ship detection
- 🌊 Sea state estimation
- 🗺️ SAR image segmentation

## 🔗 References

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN): Real-ESRGAN is a practical algorithm for real-world image super-resolution applications. It enhances image resolution and quality using deep learning techniques, making it useful for improving the clarity and detail of SAR images in this dataset.
- [Copernicus Open Access Hub](https://browser.dataspace.copernicus.eu/?zoom=7&lat=45.83645&lng=10.74463&demSource3D=%22MAPZEN%22&cloudCoverage=30&dateMode=SINGLE): Provides access to satellite data for Earth observation.
- [GDAL GitHub Repository](https://github.com/OSGeo/gdal): A powerful library for reading, writing, and transforming geospatial data formats.



