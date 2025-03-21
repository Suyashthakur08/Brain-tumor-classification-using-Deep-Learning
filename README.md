# Brain Tumor Classification using Deep Learning

## Overview
This project is focused on classifying brain tumors using deep learning models trained on MRI scan images. The classification is performed using a convolutional neural network (CNN) architecture.

## Dataset
The dataset consists of MRI scans labeled into categories representing different types of brain tumors. The images are preprocessed and augmented to improve the model's robustness.

Dataset used: [Brain Tumor Classification MRI](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

## Model Architecture
A deep learning model utilizing convolutional neural networks (CNNs) was trained using TensorFlow and Keras. The training process involved multiple epochs with batch normalization, dropout layers, and data augmentation to enhance performance.

## Training Details
- **Epochs:** 20
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Metrics:** Accuracy
- **Batch Size:** 32

## Results
- **Training Accuracy:** 94.32%
- **Training Loss:** 0.1498
- **Validation Accuracy:** 78.23%
- **Validation Loss:** 0.6656

## Dependencies
To run this project, install the following dependencies:
```bash
pip install tensorflow keras numpy matplotlib scikit-learn opencv-python albumentations
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository_link>
   cd brain-tumor-classification
   ```
2. Run the Jupyter Notebook or Python script to train and evaluate the model:
   ```bash
   python train.py
   ```

## Sample Predictions
The model provides classifications for given MRI scans, assisting in brain tumor detection. Sample predictions can be visualized using Matplotlib.

## Future Improvements
- Fine-tuning hyperparameters for better generalization.
- Implementing advanced architectures like ResNet and EfficientNet.
- Increasing dataset diversity to improve model robustness.

## Acknowledgments
- **Dataset:** Brain Tumor Classification MRI Dataset
- **Libraries:** TensorFlow, Keras, OpenCV, Albumentations, and scikit-learn.
