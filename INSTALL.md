# Installation Guide

Welcome to the installation guide for our project. This guide will walk you through the setup process for two crucial components necessary for running our applications: **TensorFlow with GPU support** and **Yolo V8**. By following these steps, you will prepare your environment to leverage TensorFlow's powerful machine learning capabilities with GPU acceleration and deploy Yolo V8 for advanced object detection tasks.

We have provided detailed instructions to ensure compatibility and ease of installation.

## Prerequisites
Before you begin, ensure your system meets the following requirements:
- **Python**: We use the latest version, Python 3.10. Ensure that Python 3.10 (or other) is installed on your system.
- **CUDA-capable GPU**: This is optional but recommended for TensorFlow GPU support. Ensure that your GPU is compatible with the required CUDA and cuDNN libraries.


# TensorFlow with GPU Support

To install TensorFlow with GPU support, follow these steps:

```sh
python3 -m pip install tensorflow
```

Verify the installation and check if TensorFlow can access the GPU:

```sh
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
```

## Additional Steps for GPU Support

1. **Install NVIDIA GPU Driver**: Ensure that you have the appropriate NVIDIA driver installed for your GPU.
2. **Install CUDA Toolkit**: Download and install the CUDA toolkit from NVIDIA's official website.
3. **Install cuDNN**: Download and install the cuDNN library from NVIDIA's website.
4. **Set Environment Variables**: Ensure that the environment variables are set correctly for CUDA and cuDNN.

## Alternative: Using Kaggle or Google Colab

If you prefer not to install the GPU support locally, you can use online platforms like Kaggle or Google Colab, which offer free access to GPUs. These platforms have the necessary libraries and drivers pre-installed, allowing you to use GPU accelerators without additional setup.

- **Kaggle**: Provides free access to GPUs for running notebooks.
- **Google Colab**: Offers free access to GPUs and TPUs. You can choose the accelerator type in the notebook settings.

### Using a GPU in Google Colab:

1. Open your Colab notebook.
2. Go to `Runtime` > `Change runtime type`.
3. Select `GPU` from the `Hardware accelerator` dropdown menu.
4. Click `Save`.

This way, you can leverage GPU acceleration without needing to install and configure the hardware and software dependencies on your local machine.


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
