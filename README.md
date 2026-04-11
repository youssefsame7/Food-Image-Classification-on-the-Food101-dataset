#  Food101 Image Classification Project

##  Overview

This project demonstrates a complete **end-to-end computer vision workflow** for image classification using the **Food101 dataset**.

It covers two main approaches:

1. Building a **custom CNN architecture (TinyVGG)** from scratch
2. Applying **Transfer Learning** to improve performance

Additionally, the project integrates **TensorBoard** for experiment tracking and performance visualization.

---

##  Objectives

* Understand the full pipeline of a computer vision project
* Implement and train a CNN model from scratch
* Improve results using transfer learning
* Track experiments and visualize metrics using TensorBoard

---


## Approaches

### 1. Custom CNN (TinyVGG)

* Built a lightweight CNN inspired by VGG architecture
* Trained from scratch on the Food101 dataset
* Covered:

  * Data loading & preprocessing
  * Model building
  * Training & evaluation

 **Insight:**
While the model learns meaningful patterns, performance is limited due to training from scratch on a relatively complex dataset.

---

### 2️. Transfer Learning 

* Used a **pre-trained model** as a feature extractor
* Fine-tuned layers to adapt to Food101
* Achieved significantly better accuracy and faster convergence

 **Improvements:**

* Better generalization
* Reduced training time
* Higher validation accuracy

---

## Experiment Tracking (TensorBoard)

* Logged:

  * Training & validation loss
  * Accuracy curves
  * Model performance over epochs

To launch TensorBoard:

```bash
tensorboard --logdir=runs
```

---

## Tech Stack

* Python
* PyTorch
* Torchvision
* TensorBoard

---


## Key Learnings

* Building models from scratch helps understand **core CNN concepts**
* Transfer learning is **essential for real-world performance**
* Experiment tracking is critical for comparing models effectively

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Data augmentation strategies
* Trying advanced architectures (EfficientNet, ResNet)
* Deploying the model (Streamlit / API)

---

## This project is part of my learning journey — the code is mostly based on [ZTM PyTorch for Deeplearning](https://www.udemy.com/share/107xb23@8HwWMtc_jgt-A80_71Kd0uYcQnkt-6BPaiqSmKcdp7KZTVQL6-sOfHjbHEgjULHv3g==/), but the explanations and experiments are my own.
