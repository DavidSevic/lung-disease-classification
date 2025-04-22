# Lung Disease Classification on Chest X-Rays

This project explores deep learning techniques for classifying lung diseases using the **ChestX-ray14** dataset. The focus was not only on achieving good performance but also on exploring **transfer learning**, **model architecture tuning**, and **evaluation strategies** relevant to medical imaging.

## 🩻 Dataset

- **ChestX-ray14**: A large-scale public dataset of chest X-ray images, including over 100,000 frontal-view X-rays with 14 disease labels.
- Download and more details: [ChestX-ray14 on PapersWithCode](https://paperswithcode.com/dataset/chestx-ray14)

## 🧠 Approach

- Utilized **transfer learning** with pre-trained CNN models from `torchvision`, including:
  - `ResNet50`
  - `VGG16`
  - `DenseNet121`
- Only the final classification layer was fine-tuned to adapt to the lung disease classification task.

## 🔧 Techniques Applied

- **Model Customization**: 
  - Tried different sizes for the final linear layer
  - Added dropout layers for regularization
- **Training Strategy**:
  - Explored different hyperparameter combinations (learning rate, weight decay)
  - Early stopping based on validation loss
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC and PR-AUC for deeper insight into classification performance

## 📁 Files

- `project.ipynb`: Main notebook containing the full implementation, results, and comments (in Serbian). Variables and function names are in English.

## ℹ️ Notes

- The project emphasizes methodology, experimentation, and understanding of model behavior over maximizing performance.
- Code comments are written in **Serbian**, while all function and variable names are in **English** for clarity.
