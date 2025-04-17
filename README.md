# 🧠 Fingerprint Classification using Deep Learning + Sobel Features

This project focuses on fingerprint type classification (thumb, index, middle, ring, little) using deep learning techniques. It combines classical edge detection (Sobel) with three modern architectures:

- EfficientNet-B0
- Vision Transformer (ViT-B/16)
- ResNet50

---

## 📚 Dataset

We use the [SOCOFing Dataset](https://www.kaggle.com/datasets/ruizgara/socofing) (6000 images).

To run this project:
1. Download the dataset from the link above
2. Extract it to a folder like `data/SOCOFing/`

---
Create a Conda Env.
Install & Run Jupyter Notebook
Establish SSH Connection with local device
Open Local browser. Conncet to the localhost:8888 using token.

## 🔧 Installation

Install the required dependencies:

```bash
pip install torch torchvision opencv-python kornia scikit-learn matplotlib seaborn


Train the model:
Run The Model.

## Results

| Model         | Accuracy | F1 Score |
|---------------|----------|----------|
| EfficientNet  | 78%      | 78%      |
| ViT           | 78%      | 78%      |
| ResNet50      | 78%      | 78%      |

## Future Work
- Add Firefly/BAT optimization
- Use invariant features
- Build a web demo

## Author
Md Farhan Zaman  
Email: farhanzaman7843@gmail.com  
GitHub: [Farhan7843](https://github.com/Farhan7843)
