```markdown
# Face Classification using Deep Learning 🧠📸

This repository contains a complete pipeline for training and evaluating a deep learning model to perform face identification across thousands of classes using transfer learning with PyTorch.

## 🚀 Features
- Custom `FaceDataset` for labeled images and `TestDataset` for unlabeled test set.
- Preprocessing pipeline with strong data augmentations and ImageNet normalization.
- Supports multiple pretrained backbones: `ResNet50`, `EfficientNet-B0`, `GoogLeNet`, `VGG16`, and more.
- Stratified data splitting into train/val/test sets.
- Handles corrupted/missing images gracefully.
- Modular codebase for easy expansion.


## 🔧 Installation

```bash
git clone https://github.com/Abubakar-Imran/Facial-Classification.git
cd Face-Classification
pip install -r requirements.txt
```

## 🧠 Backbones Supported
- [x] ResNet50
- [x] EfficientNet-B0
- [x] GoogLeNet
- [x] VGG16
- [ ] Xception (via `timm`)

## 📜 License

This project is licensed under the MIT License.

---

Made with ❤️ by Abubakar Imran
```
