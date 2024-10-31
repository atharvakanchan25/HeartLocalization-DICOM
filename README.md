# HeartLocalization-DICOM
Cardiac detection model for localizing the heart in medical DICOM images using bounding box annotations.

# Heart Detection Model

This project focuses on cardiac detection in medical DICOM images, specifically by identifying and visualizing bounding boxes around the heart. The model leverages labeled data from the RSNA pneumonia detection challenge dataset to train and test the localization task.

## Project Overview
This notebook preprocesses and visualizes heart detection data:
- **Bounding Boxes**: Annotates heart locations in each image.
- **Visualization**: Displays bounding boxes on images to ensure accuracy.

## Dataset
The dataset includes DICOM images with labeled bounding boxes around the heart regions:
- **Images**: DICOM format files from the RSNA pneumonia detection dataset.
- **Labels**: CSV file with bounding box coordinates for the heart regions.

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/your-atharvakanchan25/Heart-Detection-Model.git
   cd Heart-Detection-Model

2. Ensure you have the DICOM dataset and label CSV file in the specified directories.

Usage
Open the notebook Heart Detection Final.ipynb and run the cells sequentially. The notebook will:
a) Load and preprocess DICOM images.
b) Display images with annotated bounding boxes for verification.

## Libraries Used
pydicom: For reading and handling DICOM files.
OpenCV: For resizing images.
Pandas: For data manipulation.
Matplotlib: For visualization.

## Example Visualization
Here’s a sample image with a bounding box around the heart:
![image](https://github.com/user-attachments/assets/ed36b289-566a-4712-b1dc-f5b28c002f5c)


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
