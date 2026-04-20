# 🌿 Plant Disease Detection using Deep Learning (ResNet50)

## 📌 Overview

This project uses **Deep Learning and Transfer Learning** to detect plant diseases from leaf images. It leverages the **PlantVillage dataset** and a pretrained **ResNet50 model** to classify plant leaves into healthy or diseased categories.

---

## 🚀 Features

* 📷 Image-based plant disease detection
* 🧠 Transfer learning using ResNet50
* 📊 Model evaluation with accuracy & confusion matrix
* 🔍 Predict disease from new input images
* 📁 Automatic dataset handling using Kaggle API

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy, Matplotlib
* Scikit-learn
* Kaggle API

---

## 📂 Dataset

Dataset used: **PlantVillage Dataset**

* Contains labeled images of plant leaves
* Includes multiple crops and diseases

---

## ⚙️ How it Works

1. Download dataset using Kaggle API
2. Preprocess images (resize, normalization)
3. Split into training & validation sets
4. Load pretrained **ResNet50** model
5. Train model on dataset
6. Evaluate performance
7. Predict disease from new images

---

## 🧪 Model Architecture

* Base Model: ResNet50 (pretrained on ImageNet)
* Custom Layers:

  * Global Average Pooling
  * Dense layers
  * Dropout (for regularization)
* Output Layer:

  * Softmax (multi-class classification)

---

## 📊 Results

* Achieves good accuracy on validation data
* Visualized using:

  * Accuracy plots
  * Confusion matrix
  * Classification report

---

## 🔮 Prediction

You can test the model with your own leaf images:

```python
predict_image_class(model, "leaf.jpg", class_indices)
```

---

## 📁 Output Files

* `class_indices.json` → maps class labels
* Trained model (optional save)

---

## 💡 Future Improvements

* Deploy as a mobile/web app 📱
* Add real-time camera detection
* Improve accuracy with data augmentation
* Use more advanced architectures (EfficientNet, Vision Transformers)

---

## 🤝 Applications

* Smart farming 🌾
* Agricultural automation
* Early disease detection

---

## 📜 License

This project is for educational purposes.

---

## ⭐ Acknowledgements

* PlantVillage Dataset
* TensorFlow & Keras
* Kaggle

---
