Satellite Land Use Classifier

A deep learning-based approach for satellite image classification to support tourism and real-estate planning.

Project Overview

This project uses satellite imagery and deep learning models (CNNs) to classify land use patterns, such as:
- Urban
- Forest
- Water bodies
- Agricultural land
- Barren land

The insights can help in:
- Identifying potential tourist zones
- Real estate development analysis
- Sustainable land management

Tech Stack

- Python
- TensorFlow / Keras or PyTorch
- OpenCV / PIL
- NumPy / Pandas
- Matplotlib / Seaborn
- QGIS / Google Earth Engine (optional)

Dataset

- Source: EuroSAT, DeepGlobe Land Cover, or Google Earth Engine
- Format: RGB satellite images (64x64 or 224x224)

Model Workflow

1. Data Preprocessing  
   Normalize, resize, and augment images

2. Model Training  
   Train CNN on classified land types

3. Evaluation  
   Accuracy, confusion matrix, and F1-score

4. Prediction and Mapping  
   Map outputs to regions of interest

Example Output

| Input Image | Predicted Class |
|-------------|------------------|
| ![img](example1.png) | Urban |
| ![img](example2.png) | Waterbody |

Future Improvements

- Add semantic segmentation using U-Net or DeepLabV3
- Integrate with Google Maps API
- Deploy a Streamlit dashboard for interactive results
