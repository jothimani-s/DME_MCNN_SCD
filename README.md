# DME Detection with Enhanced Multi-feature Fusion Network (MCNN + SCD)

This repository contains the code and resources for the paper titled:
**"Early Detection of Diabetic Macular Edema Using Multi-feature Fusion Deep Learning Network with Spatial Channel Dropout."**

## 🧠 Model Overview
This model uses a hybrid CNN architecture (MCNN) with Spatial Channel Dropout (SCD) to detect macular edema from retinal fundus images. Grad-CAM is used for interpretability.

## 📁 Folder Structure
- `main_model.py` - Code for training and evaluating the MCNN+SCD model.
- `preprocessing.py` - Image preprocessing including Retinex enhancement, normalization, and resizing.
- `utils.py` - Helper functions for metrics, Grad-CAM generation, etc.
- `config.py` - Configuration settings for training.
- `README.md` - Project documentation.

## 🚀 Requirements
- Python 3.8+
- TensorFlow 2.6 / Keras 2.4.3
- OpenCV, NumPy, Matplotlib, Scikit-learn

Install dependencies using:
```bash
pip install -r requirements.txt
```

## 🔧 How to Run
```bash
python main_model.py
```

## 📊 Outputs
- Accuracy, Precision, Sensitivity, Specificity, F1-Score
- Grad-CAM heatmaps for interpretability

## 📂 Data Access
This code supports IDRiD, MESSIDOR, HEI-MED, and Aravind datasets. Public datasets can be downloaded from their respective sources. Due to privacy, Aravind data is not included.

## 📜 License & Citation
For research use only. Cite the original paper if used.

