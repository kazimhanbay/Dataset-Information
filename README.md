# 🛰️ Dataset-Information

This dataset contains satellite images processed into 800x800 pixel segments. The dataset aims to aid in the development and evaluation of ship detection algorithms using synthetic aperture radar (SAR) imagery and has been verified by SAR experts.

## 📊 Dataset Description Version 1

The first version of the dataset is divided into two main categories:

1. **🚢 Ship**: Contains images with various types of ships and includes 10,000 images.
2. **🌊 Sea**: Contains images of the sea without ships and includes 10,000 images.

### Example
![Ship and Sea Image Dataset](https://github.com/user-attachments/assets/35bd9d26-ff40-493e-a556-dfefe597a971)

## 📊 Dataset Description Version 2

The second version of the dataset has been processed using real-esrgan and contains categories such as land/ship/sea and ship.

The second version of the dataset is divided into two main categories:

1. **🚢 Ship**: Contains images with various types of ships.
2. **🌊🚢🏝️ Sea/Ship/Land**: Contains images of the mix (sea, ship, land).

### Example
![version2](https://github.com/user-attachments/assets/6e934c9b-fe39-41c5-ab2f-231529682ced)

Note: The two categories consist of a total of 10,000 images.

## 🖼️ Image Specifications

- **Resolution**: The data were acquired in IW mode.
- **Size**: Each image segment is 800x800 pixels.
- **Polarization Types**: The dataset images are provided with VV and VH polarizations.

## 📝 Annotations

The verification process was carried out entirely by SAR experts without relying on AIS data or Google Earth.

## 📚 Usage

This dataset can be used for training and testing machine learning models for tasks such as:

- 🚢 Ship detection
- 🌊 Sea state estimation
- 🗺️ SAR image segmentation
