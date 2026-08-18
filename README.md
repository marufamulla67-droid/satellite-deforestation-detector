# 🛰️ Satellite Deforestation Detector

An end-to-end Deep Learning pipeline built using **PyTorch** and **ResNet** architecture to monitor and classify deforestation patterns using Sentinel satellite imagery.

---

## 📌 Features
*  **Custom Dataset Loader:** Preprocesses and normalizes multispectral satellite images.
* **ResNet Model Architecture:** Transfer learning with ResNet for high classification accuracy.
* **Automated Metrics:** Evaluates Precision, Recall, F1-Score, and Loss curves during training.
* **Google Colab Integration:** Ready-to-run notebook workflow directly linked with GitHub.

---

## 📂 Project Structure

```text
├── README.md
├── resnet_sentinel.ipynb
├── data/              # Satellite imagery dataset (Sentinel)
├── models/            # Saved model checkpoints (.pt / .pth)
└── outputs/           # Training logs and confusion matrix plots
