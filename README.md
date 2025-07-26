## Deep Learning Projects for Robotics & Vision

A collection of hands-on deep learning projects focused on robotics applications, real-time inference, and computer vision.

---

## Project 1: CIFAR-10 CNN Classifier + 3D Reconstruction

### Objective
- Build a CNN from scratch using PyTorch to classify images from CIFAR-10.
- Improve performance with regularization, batch normalization, and data augmentation.
- Visualize results using confusion matrices.
- Reconstruct 3D scenes from 2D images using MiDaS + Open3D.

---

## Tech Stack
- `PyTorch`, `torchvision`
- `OpenCV`, `Matplotlib`
- `Open3D`
- `MiDaS` model from `torch.hub`

---

### Results

| Technique | Accuracy |
|----------|----------|
| Basic CNN | ~46% |
| With BatchNorm + Aug | ~48.5% |

Confusion matrix, model checkpoints, and point cloud exports (`.ply`) included.

---

### 3D Reconstruction Preview

- Used MiDaS to estimate depth
- Open3D to convert into point cloud
- Real-time depth visualization

<img src="images/3d-reconstruction-elephant.png" width="600"/>

---

##Run the Project

#### 1. Clone the repo
```bash
git clone https://github.com/Vinay-Orsu/cv-dl-projects-2025.git
cd cv-dl-projects-2025/project1-cnn/
