# greek-paGAN

## Goal
In this exercise, we aim to perform classification and generation tasks on a dataset of ancient Greek characters. A more detailed explanation is available in the accompanying report file.

# dataset
## classification
The original dataset is available from the ICDAR 2013 competition [here](https://faubox.rrze.uni-erlangen.de/getlink/fi8qaEMwMkc5L2Bg7tdh5L/HomerCompTraining.zip). For this exercise, we are using cropped images of each character on the papyrus, which can be downloaded [here](https://www.dropbox.com/scl/fo/xmzzg3rks3f9xf0s5i4bz/ABAEORqLtKzgfCxIqjGahPg?rlkey=mtr91csjom9h1274ppeem2gss&st=igv0rka5&dl=0).

# Install
## Tensorflow
Source code : https://www.tensorflow.org/install/pip
```bash
python3 -m pip install tensorflow[and-cuda]
# Verify the installation:
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
```

## Yolo V8
Source code: https://pypi.org/project/ultralytics/
```bash
conda create --name yolo python=3.10
pip install ultralytics
pip install ipykernel
```

## Folders's content
- 

## Team member's
- Carolina Macedo *alias* carolisteia
- Fengyi Chen *alias* chenfen11
- Gaetan Drouet *alias* Gaetandrouet
- Nana Maglakelidze *alias* Nanamaglakelidze
- Emilie Guido *alias* Emiliegd14
