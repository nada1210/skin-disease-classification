# Skin Lesion Classification using Deep Learning

This repository contains the source code for my graduation project: a Comparative Analysis of **InceptionResNetV2** and **ResNet50V2** for diagnosing 8 types of skin cancer.

##Project Overview
* **Goal:** Automate the classification of dermatoscopic images into 8 disease classes (Melanoma, Nevus, etc.).
* **Dataset:** [ISIC 2019 / HAM10000] (https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset).
* **Best Model:** InceptionResNetV2 (Accuracy: 94.2%).

## Architectures
We implemented and compared two Transfer Learning models:
1.  **InceptionResNetV2:** Selected for its multi-scale feature extraction capabilities.
2.  **ResNet50V2:** Used as a lightweight benchmark for efficiency comparison.

## Installation & Usage
To run the notebook:
1.  Open `Skin_disease_Classification.ipynb` in kaggle.
2.  Ensure `train_ds` and `val_ds` paths point to your dataset.
3.  Install dependencies:
    ```bash
    pip install tensorflow pandas matplotlib seaborn scikit-learn
    ```

## Results
| Model | Accuracy | F1-Score |
| :--- | :--- | :--- |
| **InceptionResNetV2** | **94.2%** | **0.93** |
| ResNet50V2 | 89.1% | 0.88 |

## Model 
[[LINK TO GOOGLE DRIVE](https://colab.research.google.com/drive/1qO158yEkf6CJUzK0tDwyilQbiox0BrEd?usp=drive_link)]

## Credits
* Supervised by: [eng. haidy, dr mohamed sayed]
* Team Members: [Nada mohamed, Taha mohamed, Ehab Mokhtar, Abdelrahman Mohamed, Ahmed Ismaiel]
