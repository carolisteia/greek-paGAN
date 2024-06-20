# Installation Guide

Welcome to the installation guide for our project. This guide will walk you through the setup process for two crucial components necessary for running our applications: **TensorFlow with GPU support** and **Yolo V8**. By following these steps, you will prepare your environment to leverage TensorFlow's powerful machine learning capabilities with GPU acceleration and deploy Yolo V8 for advanced object detection tasks.

We have provided detailed instructions to ensure compatibility and ease of installation.

## Prerequisites
Before you begin, ensure your system meets the following requirements:
- **Python**: We use the latest version, Python 3.10. Ensure that Python 3.10 (or other) is installed on your system.
- **CUDA-capable GPU**: This is optional but recommended for TensorFlow GPU support. Ensure that your GPU is compatible with the required CUDA and cuDNN libraries.


## TensorFlow with GPU Support
To install TensorFlow with GPU support, follow these steps:
```bash
python3 -m pip install tensorflow
# Verify the installation and check if TensorFlow can access the GPU:
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
```

## Yolo V8

To install Yolo V8 in a dedicated conda environment, use the following commands:

```bash
conda create --name yolo python=3.10
conda activate yolo
pip install ultralytics
pip install ipykernel
```
By the end of this guide, you will have a fully functional environment ready for developing and testing applications using TensorFlow and Yolo V8. 

## Resources
1. [TensorFlow with GPU Support](https://www.tensorflow.org/))
2. [Yolo V8 Installation](https://datascientest.com/you-only-look-once-tout-savoir)
