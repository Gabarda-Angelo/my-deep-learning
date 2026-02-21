# PyTorch Deep Learning Projects

## Overview

This repository documents hands-on work focused on building, training,
optimizing, and deploying deep learning models using the PyTorch
framework. It follows a structured progression from foundational
concepts to advanced architectures and real-world deployment workflows.

The goal of this project is to develop practical skills in designing
neural networks, applying them to real datasets, and preparing trained
models for production environments.


## Project Structure

This project separates **code**, **data**, and **artifacts** to ensure
clean version control, scalability, and reproducibility.

-   Code is version-controlled using Git.
-   Large datasets and experiment outputs are stored externally.
-   The repository remains lightweight and focused on implementation.


## Google Drive Storage Architecture

![Google Drive Structure](main%20backup.png)

All large files are stored in Google Drive to avoid pushing heavy
datasets and artifacts to GitHub.

### Folder Organization

**my-deep-learning/**

This folder contains all project-related storage, including:

-   Raw datasets used for training and validation\
-   Processed datasets\
-   Trained model checkpoints\
-   Saved weights\
-   Experiment logs\
-   Evaluation results\
-   Exported models (e.g., ONNX format)

Data and artifacts are logically separated inside this main directory to
maintain clarity between:

-   Input data (datasets)
-   Generated outputs (models, logs, metrics)


## Why This Setup Matters

This structure provides several advantages:

-   Keeps the GitHub repository small and efficient\
-   Prevents large file upload issues\
-   Protects raw datasets from accidental modification\
-   Makes experiments reproducible\
-   Supports scalable storage as projects grow\
-   Follows real-world machine learning engineering practices

Google Drive acts as centralized storage for large files, while Git
handles source code and version tracking.


## Learning Progression

### 1. Foundations of PyTorch and Neural Networks

-   Understanding tensors and tensor operations\
-   Building neural networks using torch.nn\
-   Forward and backward propagation\
-   Training loops and optimization\
-   Loss functions and evaluation metrics\
-   Validation and generalization techniques


### 2. Applied Deep Learning (Computer Vision & NLP)

-   Working with datasets using TorchVision\
-   Implementing and improving CNN architectures\
-   Transfer learning and fine-tuning\
-   Transformer-based NLP models\
-   Hugging Face integration

Projects include: - Image classification\
- Text classification\
- Image segmentation


### 3. Advanced Architectures and Optimization

Explored architectures:

-   Siamese Networks\
-   ResNet\
-   DenseNet\
-   Transformers

Optimization techniques:

-   Hyperparameter tuning\
-   Pruning\
-   Quantization\
-   ONNX model export\
-   Experiment tracking with MLflow


## Applied Learning Projects

Throughout this repository, models were:

-   Built from scratch\
-   Trained and validated on real datasets\
-   Fine-tuned using transfer learning\
-   Optimized for inference efficiency\
-   Prepared for deployment

The projects integrate both computer vision and natural language
processing tasks, reflecting modern AI engineering workflows.


## Key Skills Developed

-   Deep understanding of the PyTorch framework\
-   Neural network architecture design\
-   Model training and evaluation\
-   Transfer learning\
-   Model optimization techniques\
-   Deployment preparation workflows


## Outcome

This repository demonstrates the ability to:

-   Develop deep learning systems from concept to deployment\
-   Maintain clean data and artifact management\
-   Apply best practices in machine learning engineering\
-   Build scalable and reproducible AI workflows 

## Course Reference

PyTorch for Deep Learning Professional Certificate\
https://www.coursera.org/professional-certificates/pytorch-for-deep-learning

