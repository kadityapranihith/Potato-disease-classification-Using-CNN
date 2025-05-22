# 🥔 Potato Leaf Disease Classification using CNN

This project focuses on classifying potato leaf diseases using a Convolutional Neural Network (CNN). The model identifies three categories of leaves:

- **Healthy**
- **Early Blight**
- **Late Blight**

We used the [PlantVillage Potato Leaf Dataset from Kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village), which provides images organized in folders by disease type.

---

## 📁 Dataset

- **Source**: [PlantVillage Potato Leaf Dataset on Kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)
- **Classes**: `Healthy`, `Early Blight`, `Late Blight`
- **Structure**: Each class is in a separate folder.

---

## 🧪 Data Augmentation

To improve model performance and reduce overfitting, we applied the following augmentations:

- Rotation
- Horizontal and Vertical Flip
- Rescaling

---

## 🧠 Model Architecture

A custom Convolutional Neural Network (CNN) was built with the following layers:

- **4 Convolutional Layers**
- **ReLU Activations**
- **MaxPooling Layers**
- **1 Dense (Fully Connected) Layer**
- **Softmax Output Layer**

---

## ⚙️ Training Details

- **Epochs**: 20
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Validation Split**: 20%

---

## 📊 Results

| Dataset    | Accuracy |
|------------|----------|
| Training   | 100%   |
| Validation | 98.44%   |
| Test       | 98.33%   |

---

## 📈 Visualizations

- Plotted predictions on sample test images.
- Visualized class-wise accuracy and model predictions.

---


