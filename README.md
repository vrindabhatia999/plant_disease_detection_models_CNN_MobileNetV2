# PLANT_DISEASE_DETECTION_MODELS_CNN_MobileNetV2
Plant disease repo for crops disease detection (base models) (kaggle notebooks)

# Plant Disease Detection - Base Models

Collection of baseline CNN models using MobileNetV2 for plant disease classification across multiple crops.

## 🌾 Models Included

| Crop | Diseases | Notebook |
|------|----------|----------|
| Rice | 6 classes | `rice_disease_detection.ipynb` |
| Tomato | 10 classes | `tomato_disease_detection.ipynb` |
| Potato | 3 classes | `potato_disease_detection.ipynb` |
| Wheat | 3 classes | `wheat_disease_detection.ipynb` |
| Mango | 8 classes | `mango_disease_detection.ipynb` |
| Pepper | 2 classes | `pepper_disease_detection.ipynb` |

## 🏗️ Architecture

- **Base Model:** MobileNetV2 (pretrained on ImageNet)
- **Input Size:** 224×224×3
- **Transfer Learning:** Fine-tuned on crop-specific datasets
- **Framework:** TensorFlow/Keras

## 📊 Performance

Dataset accuracy ranges: **85-98%**

*Note: These are baseline models trained on clean datasets. Real-world performance may vary.*

## 🚀 Usage

1. Open desired notebook in Jupyter/Colab
2. Run all cells to train model
3. Models saved automatically after training

## 📦 Requirements
```
tensorflow>=2.10.0
keras>=2.10.0
numpy
pandas
matplotlib
pillow
```

## 📂 Datasets

Models trained on publicly available plant disease datasets from Kaggle and PlantVillage.

## 📝 Note

These are baseline models. For production deployment with safety improvements (RLHF, calibration), see separate repository.

---

**Author:** Vrinda Bhatia  
**Last Updated:** February 2026
