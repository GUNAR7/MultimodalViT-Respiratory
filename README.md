# Multimodal Vision Transformer for Respiratory Disease Classification

A dual-branch Vision Transformer (ViT) that classifies respiratory diseases
(COVID-19, Pneumonia, Tuberculosis, Normal) using CT Scan and Chest X-ray images simultaneously.

## Results
| Class | Precision | Recall | F1 Score |
|---|---|---|---|
| COVID-19 | 91% | 89% | 90% |
| Pneumonia | 86% | 84% | 85% |
| Tuberculosis | 88% | 90% | 89% |
| Normal | 90% | 92% | 91% |
| **Overall** | | | **~88%** |

## Architecture
![Architecture](docs/multimodal_vit_architecture.svg)

## Tech Stack
- Python, TensorFlow, Keras
- OpenCV, NumPy, scikit-learn, nibabel
- Trained on Kaggle (GPU)

## Team
- R. Guna Vardhan — 2022BCSE07AED099
- K. Nithin Kumar
- G. Sai Smaran
- N. Girish

## Faculty Guide
Dr. A. Ezil Sam Leni
