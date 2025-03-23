# CelebA Spoof Detection using Vision Transformer (ViT)

This repository contains the fine-tuning of a Vision Transformer (ViT) model for face anti-spoofing using the CelebA Spoof dataset. The goal is to classify images as real or spoofed to enhance face authentication security.

## Project Overview
We fine-tuned a pre-trained ViT model on the CelebA Spoof dataset following these steps:
1. **Dataset Preparation**: Splitting the `nguyenkhoa/celeba-spoof-for-face-antispoofing-test` dataset into training and testing sets.
2. **Preprocessing**: Organizing images into `celeba_spoof/train` and `celeba_spoof/test` directories.
3. **Model Fine-Tuning**: Adapting a pre-trained Vision Transformer (ViT) model for binary classification.

## Dataset
- **CelebA Spoof Dataset**: Contains images labeled as real or spoofed, used for training and testing.
