# Image Classification using CNN

This project implements an **Image Classification system** using a Convolutional Neural Network (CNN) in Python. It takes images as input, preprocesses them, trains a model, and predicts the class of new images.

## Project Workflow

1. **Prepare Dataset**  
   Organize images into subfolders inside `data/` (e.g., `data/happy/` and `data/sad/`).

2. **Clean Images**  
   Remove corrupted or unsupported images using Pillow.

3. **Preprocess Images**  
   Resize, normalize, and convert images to tensors suitable for model training.

4. **Train Model**  
   Train a CNN on the dataset using `main.ipynb`.

5. **Evaluate & Predict**  
   Test the trained model on new images and visualize predictions.

6. **Save Model**  
   Save the trained model in `.keras` format for future use.

## Requirements
 
- TensorFlow / Keras  
- OpenCV  
- Pillow  
- Matplotlib  
- NumPy  
