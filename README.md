# Image and Video Generation from Segmentation Maps

This project focuses on generating realistic images and videos from segmentation maps using a conditional GAN (Pix2Pix) framework. The model is trained with extensive one-shot data augmentation using Thin Plate Spline (TPS) to enhance generalization from minimal data.

## 🔍 Overview

- Developed a **Pix2Pix cGAN-based** pipeline to synthesize high-quality images from segmentation maps.
- Employed **Thin Plate Spline** transformations to augment a single image–segmentation pair into a rich dataset.
- Extended the image generation process to **frame-wise video generation** using OpenCV and PyTorch.

## 🧠 Key Features

- One-shot training using segmentation-image pair with TPS augmentation.
- Conditional image synthesis based on primitive representations.
- Video synthesis from generated frames.
- Modular, easily extensible codebase built with PyTorch.

## 🛠️ Technologies Used

- Python
- PyTorch
- Pix2Pix (cGAN)
- Thin Plate Spline (TPS)
- OpenCV
- NumPy
- Matplotlib

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/rishikeshnanaware/Segmentation-Maps.git
cd Segmentation-Maps
pip install -r requirements.txt
