# Handwritten Digit Recognition

## Project Overview
This project aims to achieve **handwritten digit recognition** using a **VGG-like neural network**, trained on the **SVHN (Street View House Numbers) dataset**. The goal is to optimize classification accuracy through hyperparameter tuning and data augmentation.

## Methodology
- **Dataset**: SVHN (Street View House Numbers)
- **Data Augmentation**: Rotation, resizing, aspect ratio adjustments, and normalization.
- **Model**: Three convolutional blocks with batch normalization, ReLU activation, and max pooling.
- **Training**: Adam optimizer, learning rate 0.001, batch size 64, and cross-entropy loss.
- **Evaluation**: Test loss, accuracy, and ROC AUC scores.

## Results
- **Best Performance**: Learning rate = 0.001, batch size = 64, optimizer = Adam.
- **Accuracy**: 94.72%
- **Key Insights**: Proper data augmentation and optimizer selection significantly improved performance.

## Future Work
- Experiment with deeper architectures (ResNet, DenseNet).
- Apply advanced augmentation techniques (CutMix, MixUp).
- Integrate attention mechanisms for feature enhancement.

## Online Code
[Colab Notebook](https://colab.research.google.com/drive/1TMlMDdQqoA0nYKPuVDZWTgc-56BCzE2z?usp=sharing)

