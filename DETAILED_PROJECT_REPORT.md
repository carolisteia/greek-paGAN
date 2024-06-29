## Comprehensive Report on the Notebooks:

### Introduction
The project is focused on employing machine learning techniques to identify and generate ancient Greek characters. It is structured around several key activities, including dataset preparation, model training, and evaluation of generative models. The overarching goal is to explore how data augmentation and generative models can improve character recognition in damaged or incomplete texts.

### Notebook Overview
The notebooks present methodologies for the classification and generation of ancient Greek characters, employing machine learning techniques with an emphasis on synthetic data. Most parts of these notebooks were originally created by [Chahan Vidal-Gorène](https://www.chartes.psl.eu/annuaire/chahan-vidal-gorene) during Python classes for the Digital Humanities students at the Ecole Nationale des Chartes. We have adapted them to work with our dataset.

## Character Classification Notebook

### Overview
This notebook focuses on character classification using machine learning techniques. It includes steps for data preprocessing, model training, and evaluation.

### Contents
1. **Data Preparation**
    - Loading and preprocessing character images.
    - Splitting data into training, validation, and test sets.
2. **Model Definition**
    - Building and compiling a Convolutional Neural Network (CNN) model.
3. **Training**
    - Training the model on the training dataset.
    - Evaluating performance on the validation dataset.
4. **Evaluation**
    - Assessing model performance on the test dataset.
    - Generating accuracy metrics and confusion matrices.
  
   
## Character Inferences Notebook

### Overview
This notebook delves into character inferences, exploring techniques for predicting and understanding character properties based on given data. The primary objective is to classify Greek characters using the YOLO (You Only Look Once) framework.

### Key Points

1. **Data Preparation**
        - The dataset consists of images of Greek characters organized into subfolders by character.
        - Images are loaded and preprocessed using TensorFlow's image_dataset_from_directory method.

2. **Model Definition**
       - The YOLO (You Only Look Once) framework is employed for classifying character images.
       - The model leverages Convolutional Neural Networks (CNNs) to accurately categorize images into designated classes.

3. **Training**
       - The model is trained using different parameters. 
       - The model's performance is assessed using an occlusion technique commonly used in computer vision.
        
4. **Results**

    The model achieved reasonable classification accuracy but faced challenges due to the complex nature of ancient script characters.
    The generated heatmaps provided insights into the discriminative features used by the model for character classification.
    Future work should focus on refining the model architecture and exploring larger datasets to improve classification performance.

## Greek Pagan Notebook

### Overview
This notebook explores various aspects of Greek Paganism, focusing on historical, cultural, and religious contexts. It includes detailed explanations, code snippets, and visualizations to enhance understanding.

### Contents
1. **Preamble**
    - Introduction and background of the Greek Pagan project.
2. **State of the Art**
    - Overview of image classification and GAN techniques.
    - Discussion on the significance of deep learning in OCR and HTR.
3. **Image Classification Using YOLO**
    - Task description for classifying Greek characters.
    - Methodologies and dataset preparation.
    - Model definition and training details.
    - Evaluation of model performance.
4. **Synthetic Data Generation with GANs**
    - Exploring the generation of synthetic datasets using GANs.
    - Enhancing the robustness of classifiers with synthetic data.



This report provides an overview of each notebook, summarizing the main objectives, methods, and findings. Each section includes a brief description of the tasks, datasets, models, training processes, and evaluations performed in the notebooks.
















