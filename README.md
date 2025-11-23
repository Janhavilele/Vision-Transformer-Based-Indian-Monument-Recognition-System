# Vision-Transformer-Based-Indian-Monument-Recognition-System

An advanced deep-learning project built to classify Indian monuments using Vision Transformer (ViT) models. This project benchmarks multiple architectures and demonstrates why ViT-B16 is the best choice for fine-grained monument recognition.

**Project Overview:**

- This project aims to automatically classify Indian monuments from images using transformer-based architectures.
- Evaluated ViT-B16, ViT-B32, and ResNet50, comparing them using accuracy, precision, recall, and F1-score to determine the best-performing model.

**Purpose:**

India has thousands of culturally significant monuments—manually organizing or recognizing them from images is time-consuming.

This model enables:
- Fast & accurate monument identification
- Support for tourism apps, digital archiving, and heritage preservation
- Automated tagging for large image collections

**Dataset:**

A curated dataset of Indian monuments (24 classes), Preprocessed to 224×224 resolution, Train–test split: 80:20, Augmentation applied (rotation, flip, brightness variations)

**Model Comparison:**

Model	Accuracy	Precision	Recall	F1-Score
ViT-B16	0.9468	0.9452	0.9466	0.9466
ViT-B32	0.9289	0.9245	0.9459	0.9256
ResNet50	0.9112	0.9132	0.9250	0.9121


**Key Highlights:**

- ViT-B16 achieved 94.68% accuracy & 94.66% F1-score

- Excellent at capturing micro-patterns & architectural textures

- Demonstrated reliability for tourism, classification apps, and cultural datasets


