# Dataset-Information

This dataset contains satellite images processed into 800x800 pixel segments. The dataset includes images of ships and sea, verified by SAR experts. The dataset aims to aid in the development and evaluation of ship detection algorithms using synthetic aperture radar (SAR) imagery.

## Dataset Description

The first version of the dataset is divided into two main categories:

1. **Ship**: Contains images with various types of ships and contains 10,000 images.
2. **Sea**: Contains images of the sea without ships and contains 10,000 images.

## Example
![Ship and Sea Image Dataset](https://github.com/user-attachments/assets/35bd9d26-ff40-493e-a556-dfefe597a971)

### Image Specifications

- **Resolution**: The data were acquired in IW mode.
- **Size**: Each image segment is 800x800 pixels.
- **Polarization Types**: The dataset images are provided with VV and VH polarizations.


### Annotations

The verification process was carried out entirely by SAR experts without relying on AIS data or Google Earth.

## Usage

This dataset can be used for training and testing machine learning models for tasks such as:

- Ship detection
- Sea state estimation
- SAR image segmentation

