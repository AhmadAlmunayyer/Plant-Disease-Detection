# Plant Disease Detection

## Introduction
Plant diseases pose significant threats to agriculture, leading to substantial crop loss and contributing to global hunger. This project aims to develop a robust model for identifying plant diseases using advanced deep learning techniques.

## Table of Contents
1. [Introduction](#introduction)
2. [Methodology](#methodology)
3. [Datasets](#datasets)
4. [Discussion](#discussion)
5. [Conclusion](#conclusion)
6. [Related Works](#related-works)
7. [Contributors](#contributors)

## Methodology
This project utilizes the EfficientNet-B3 model, a convolutional neural network optimized for image processing. Key methodologies include:
- **EfficientNet-B3**: Chosen for its balance of efficiency and performance. It scales uniformly in depth, width, and resolution.
- **Transfer Learning**: Pre-trained weights from ImageNet were used to improve feature extraction.
- **Data Augmentation**: Techniques were applied to increase dataset size and diversity, helping the model generalize better.
- **Training**: The model was trained on an 80/10/10 split (training/testing/validation) with the Adam optimizer.

## Datasets
Two primary datasets were used:
1. **PlantVillage**: Contains images of 14 plant species with 25 different diseases.
2. **Rice Leaf Dataset**: Includes images of rice plants with various diseases.

The combined dataset provided a diverse range of 43 classes with over 119,000 images after augmentation.

## Discussion
The EfficientNet-B3 model achieved a high accuracy of 94% in plant disease identification. The merging of diverse datasets and the use of ImageNet pre-trained weights contributed to its success. The project addressed several challenges in plant disease detection, including dataset diversity and model generalization.

## Conclusion
The study demonstrates the effectiveness of using EfficientNet-B3 and a diverse dataset for plant disease detection. Future work aims to expand the dataset further and explore the use of transformers to improve accuracy.

## Related Works
This project builds on previous research in plant disease detection, including:
- Sensor-based detection systems (1985)
- Early detection using SVM (2010)
- Various machine learning and deep learning models for plant disease classification

For detailed references, please refer to the full project report.

## Contributors
- Zaid Aburashied
- Zaid Ahram
- Ibrahim Salah
- Ahmad Almunayyer
- Nour Alteeti

Supervised by: Prof. Tamam Al Sarhan

---
