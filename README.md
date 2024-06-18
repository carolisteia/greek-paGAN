# greek-paGAN

# scope
 In this exercise, we aim to do classification and generation tasks on an ancient Greek characters dataset.

# dataset
The original dataset is available on Icdar's 2013 [Competition](https://faubox.rrze.uni-erlangen.de/getlink/fi8qaEMwMkc5L2Bg7tdh5L/HomerCompTraining.zip). For this exercice, we are using the images's crops, that are available on the folder/data with a total of 35 579 images.

# Tensorflow
Source code : https://www.tensorflow.org/install/pip
```bash
python3 -m pip install tensorflow[and-cuda]
# Verify the installation:
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
```

# Folders's content
- `CR/` : dossier contenant les comptes rendus des rendez-vous de groupe
- `json/` : dossier contenant les json de nos annotations
- `notebooks/`: dossier contenant les notebook Detectron2
- `Python_HN/`: (__dossier complet exécutable__) dossier contenant le notebook final Detectron2, le répertoire contenant les images, les annotations finales et les résultats du modèle.
- `parametres_VGG.png` : capture d'écran des paramètres utilisés sur VGG pour les annotations 'humain'. 

# Team member's
- Carolina Macedo *alias* carolisteia
- Fengyi Chen *alias* 
- Gaetan Drouet *alias* Gaetandrouet
- Nana Maglakelidze *alias* Nanamaglakelidze
- Emilie Guido *alias* Emiliegd14
