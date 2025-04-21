# Brain Tumor Detection from CT Scans using Machine Learning

## 📌 Project Overview

This project detects brain tumors using CT scan images with a Convolutional Neural Network (CNN). It uses supervised learning to classify images into tumor and no_tumor categories.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Scikit-learn
- Matplotlib

## 🗂️ Project Structure

- `data/` - for storing CT scan images
- `notebooks/` - contains the Jupyter notebook for training and testing
- `models/` - stores trained model files
- `outputs/` - prediction results, metrics, visualizations
- `utils/` - helper functions
- `requirements.txt` - list of dependencies

## 🚀 How to Use

1. Install dependencies:
```
pip install -r requirements.txt
```

2. Run the Jupyter Notebook in `notebooks/tumor_detection.ipynb`.

3. Download dataset and place it under `data/`, structured as:
```
data/
├── tumor/
├── no_tumor/
```

4. Train and evaluate the model.

## 📥 Dataset

Use any public CT brain tumor dataset like from [Kaggle](https://www.kaggle.com).

