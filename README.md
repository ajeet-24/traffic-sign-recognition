cat > README.md << 'EOF'
# 🚦 Traffic Sign Recognition

A deep learning project to classify **58 categories** of traffic signs using CNNs and Transfer Learning.

## Models
- **Custom CNN** — Baseline model built from scratch
- **EfficientNetB0** — Transfer learning with two-phase fine-tuning

## Features
- Data augmentation & EDA with class distribution plots
- Two-phase transfer learning (frozen base → fine-tune last 20 layers)
- Evaluation: Accuracy, Classification Report, Confusion Matrix, ROC Curve
- Per-class accuracy visualization
- Live webcam inference (local environment)

## Dataset
[Traffic Sign Dataset Classification](https://www.kaggle.com/datasets/ahemateja19bec1025/traffic-sign-dataset-classification) — 58 classes

## Requirements
tensorflow
scikit-learn
matplotlib
seaborn
opencv-python
pandas
numpy

## Usage
Run the notebook on **Google Colab** with a T4 GPU for best performance.  
For webcam inference, run locally after downloading the saved model.
EOF