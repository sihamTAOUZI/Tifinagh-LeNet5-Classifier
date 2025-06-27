# Tifinagh Character Classification with LeNet-5

This project implements a simple **Convolutional Neural Network (LeNet-5)** for the multiclass classification of handwritten **Tifinagh script characters**.

---

## 📂 Project Structure

- `data_loader.py` — Custom PyTorch Dataset and DataLoader logic.
- `lenet5_model.py` — LeNet-5 architecture definition.
- `train.py` — Training pipeline with loss and accuracy tracking.
- `test.py` — Test evaluation and figures generation (loss curves, confusion matrix, pie chart).
- `labels-map-fixed.csv` — CSV file mapping image paths to labels (paths fixed for Colab/local use).
- `figures/` — Folder containing exported result plots (`loss_curve.png`, `accuracy_curve.png`, `test_confusion_matrix.png`, etc.).
- `requirements.txt` — Dependencies list (PyTorch, torchvision, matplotlib, scikit-learn, tqdm).

---

## 🗂️ Dataset

**Note**: The full dataset (`tifinagh-images/`) is too large for GitHub and is therefore not included here.  
👉 You can download it separately via this link (example):  
[Download full dataset](https://github.com/sihamTAOUZI/Tifinagh-LeNet5-Classifier.git)

The CSV file `labels-map-fixed.csv` shows the expected folder structure:

