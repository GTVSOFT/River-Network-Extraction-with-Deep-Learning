# River Network Extraction with Deep Learning

This repository provides a complete solution for extracting river networks from satellite imagery using deep learning, specifically using a U-Net architecture.

## Overview
- **Task**: Semantic Segmentation of river networks.
- **Model**: U-Net.
- **Data**: Satellite imagery and corresponding binary masks.
- **Libraries**: TensorFlow, Keras, Pandas, Matplotlib.

## Project Structure
- `train_image_dir`: Directory containing input images.
- `train_mask_dir`: Directory containing ground truth masks.
- `unet_model()`: Function defining the U-Net architecture.
- `train_generator()`: Generator for feeding training data.
- `val_generator()`: Generator for feeding validation data.
- `training_history.xlsx`: Excel file containing training and validation loss/accuracy per epoch.

## How to Run
1. Prepare the dataset with images and masks.
2. Update the paths to your dataset in the script.
3. Run the script to train the model.
4. Training history will be saved to `training_history.xlsx`.
5. Trained model will be saved as `river_network_unet_model.h5`.

## Requirements
- Python 3.8+
- TensorFlow 2.x
- Pandas
- Matplotlib

Install dependencies:
```bash
pip install tensorflow pandas matplotlib
```

## Output
- Trained U-Net model (`river_network_unet_model.h5`)
- Training history Excel file (`training_history.xlsx`)
- Visualization of image, mask, and prediction.

## Author
**Ebiere**

---
Feel free to fork and contribute to the project!
