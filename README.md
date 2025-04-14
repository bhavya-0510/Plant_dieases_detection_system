# 🌿 Plant Disease Classification using CNN

This project leverages Convolutional Neural Networks (CNNs) and **EfficientNetV2L** to classify plant diseases based on leaf images. It includes a complete pipeline from data loading and visualization to model training and prediction.

---

## 📁 Project Structure

- **Data Loading & Preprocessing**: Uses `ImageDataGenerator` for data augmentation and normalization.
- **Modeling**: Implements a CNN using transfer learning with `EfficientNetV2L`.
- **Training**: Optimized with Adam optimizer and enhanced using callbacks like `ReduceLROnPlateau` and `EarlyStopping`.
- **Evaluation**: Performance metrics, confusion matrix, accuracy/loss plots.
- **Prediction**: Upload your own image and get disease classification results.

---

## 🚀 Technologies Used

- Python
- TensorFlow / Keras
- EfficientNetV2L
- NumPy, Pandas
- Matplotlib, Seaborn, Plotly
- Google Colab (for GPU acceleration)

---

## 📊 Visualizations

- Class distribution of plant disease categories
- Sample training and validation images
- Accuracy and loss curves

---

## 🧠 Model Summary

- Uses `EfficientNetV2L` as a base model
- Custom dense layers with Batch Normalization and Dropout
- Final output layer with softmax activation for multi-class classification
- Trained using transfer learning and fine-tuning techniques

---

## 🧪 How to Run

1. Clone this repository
2. Make sure the dataset is structured correctly inside your working directory
3. Open the notebook in Jupyter or Google Colab
4. Run all the cells sequentially
5. For custom image predictions, update the image path in the prediction section

```bash
jupyter notebook plant_diseases_cnn.ipynb
