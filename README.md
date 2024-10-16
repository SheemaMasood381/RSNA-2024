"# RSNA-2024" 
# Lumbar Spine Degeneration Classification

This repository contains the implementation of a machine learning-based classification system for lumbar spine degenerative conditions using MRI images. The project focuses on fine-tuning multiple convolutional neural network architectures, including VGG, DenseNet, and EfficientNet, utilizing techniques such as class weights and SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Approaches](#approaches)
  - [VGG](#vgg)
  - [DenseNet](#densenet)
  - [EfficientNet](#efficientnet)
- [Performance Metrics](#performance-metrics)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Next Steps](#next-steps)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

Low back pain is a significant health concern worldwide, and accurate classification of degenerative conditions is crucial for effective diagnosis and treatment. This project leverages deep learning techniques to classify MRI images of the lumbar spine into three severity classes: Normal/Mild, Moderate, and Severe.

## Dataset

The dataset consists of MRI scans annotated with severity scores for various lumbar spine degenerative conditions. The conditions included are:

1. Left Neural Foraminal Narrowing
2. Right Neural Foraminal Narrowing
3. Left Subarticular Stenosis
4. Right Subarticular Stenosis
5. Spinal Canal Stenosis

## Approaches

### VGG

- Implementation details and results of the VGG architecture for classification.
- Description of data preprocessing, model architecture, and performance metrics.

### DenseNet

- Implementation details and results of the DenseNet architecture.
- Description of the specific modifications made to improve model performance.

### EfficientNet

- **Fine-tuning of the EfficientNet model for multi-class classification.**
- **Use of class weights and SMOTE to tackle class imbalance.**
- **Achieved an overall accuracy of 60% with notable performance on normal/mild and severe classes.**

## Performance Metrics

The model performance was evaluated using various metrics, including:

- Accuracy
- Precision
- Recall
- F1 Score
- Area Under the Curve (AUC)

**Key Findings:**
- **EfficientNet achieved the best performance with SMOTE, resulting in:**
  - Accuracy: 60%
  - AUC for normal/mild: 0.80, moderate: 0.67, severe: 0.82

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SheemaMasood381/RSNA-2024-LumbarSpine-DegenerationClassification.git


2. Navigate to the project directory:
  ```bash
  cd RSNA-2024-LumbarSpine-DegenerationClassification


3. Install the required packages:
  ```bash
  pip install -r requirements.txt


## Usage
To use the model, follow these instructions:

## Preprocess the MRI images as specified in the code.
1- Train the models (VGG, DenseNet, EfficientNet) using the provided scripts.
2- Evaluate the model performance using the evaluation metrics implemented in the code.

## Results
The detailed results of the models are available in the respective implementation files. The classification reports and confusion matrices provide insights into the model's strengths and weaknesses, particularly regarding the identification of moderate cases.

## Next Steps
Potential improvements and future work include:

  - Further optimization of hyperparameters.
  - Implementation of advanced data augmentation techniques.
  -Exploration of ensemble methods to enhance model accuracy.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Special thanks to the Radiological Society of North America (RSNA) for providing the dataset.
References to papers and resources that informed this project can be found in the project documentation.

### Notes:

1. **Adjust Sections:** Feel free to modify the content, especially in the "Approaches" section, where you may want to add more specific details about your implementations.
2. **Add Links:** If you have a `requirements.txt` file or a license file, ensure they exist in your repo; otherwise, you can remove those sections.
3. **Future Directions:** If you have specific ideas for future work or improvements, feel free to elaborate on those.


