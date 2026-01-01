# CIFAR-100 CNN (PyTorch) - Complete Training Pipeline

Deep Convolutional Neural Network for CIFAR-100 classification (100 classes).

##  Features
- **512-channel conv tower** (5 layers → 1024 final conv)
- **BatchNorm** after every conv layer
- **Dropout 0.5** before final FC
- **Data augmentation** (RandomFlip + Resize)
- **Live kernel visualization**
- **Training curves** (loss + accuracy)
- **GPU-accelerated** (auto-detect)


##  Quick Start

```bash
pip install torch torchvision matplotlib tqdm
jupyter notebook cifar100_cnn.ipynb
```
