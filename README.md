#  Handwritten Character Recognition
### CodeAlpha Machine Learning Internship : Task 3

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Accuracy](https://img.shields.io/badge/Accuracy-99.53%25-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

##  Project Overview
This project implements a **Handwritten Digit Recognition** system using **Convolutional Neural Networks (CNN)** trained on the **MNIST dataset**. The model recognizes handwritten digits (0–9) with **99.53% accuracy**. A live **Gradio-based drawing UI** lets users draw digits and get real-time predictions.

##  Model Architecture
 Conv2D + BatchNormalization + MaxPooling (x2)
 Dropout layers to prevent overfitting
 Dense layers with Softmax output

##  Results
| Metric | Value |
|--------|-------|
| Test Accuracy | 99.53% |
| Test Loss | 0.02 |
| Best Epoch | 14 |

##  Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3.10+ | Programming language |
| TensorFlow/Keras | Model building & training |
| NumPy | Data manipulation |
| Matplotlib/Seaborn | Visualization |
| Scikit-learn | Confusion matrix |
| Gradio | Live drawing UI |
| Google Colab | Training (Free GPU) |

##  How to Run
1. Open `codeAlpha_task_3.ipynb` in Google Colab
2. Runtime → Change runtime type → **GPU**
3. Run all cells
4. Gradio UI will launch automatically

##  Live Demo
Draw any digit (0-9) on the canvas and AI will predict it instantly with confidence scores!

##  Author
**Rija Malik**
 GitHub: [@rijamalik971-art](https://github.com/rijamalik971-art)


