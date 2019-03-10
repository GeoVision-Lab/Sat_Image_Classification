# Satellite Image classification with TensorFlow and Keras

CNN for multi-class image classification in TensorFlow and Keras

## 1. Structure of directories
### sub directories
<p>

```
Top
├── datasets                :locate datasets
│   └── EuroSAT_RGB         :download and unzip sample data
├── notebook                :Jupyter notebooks for users' understanding
│   └── nets                :Models in TF and Keras for the Jupyter notebooks
├── src                     :Python code for execute classification
│   ├── nets                :Models in TF and Keras
│   │   └──tfslim_nets      :Forked from tf_slim library
│   └──utils                :help functions
├── tensorboard             :output from calculation by each codes 
│   ├── keras_cnn           :result of /src/Keras_CNN_sample.py
│   ├── slim_mobilenet      :result of /src/Mobilenet_sample.py
│   └── tf_cnn              :result of /src/TF_CNN_sample.py
├── tmp                     :intermidiate files
│   ├── figures             :samples images, graph
│   │   ├── keras_cnn       :result of /src/Keras_CNN_sample.py
│   │   ├── slim_mobilenet  :result of /src/Mobilenet_sample.py
│   │   └── tf_cnn          :result of /src/
TF_CNN_sample.py
│   ├── models              :output models
│   │   ├── keras_cnn       :result of /src/Keras_CNN_sample.py
│   │   ├── slim_mobilenet  :result of /src/Mobilenet_sample.py
│   │   └── tf_cnn          :result of /src/
...
```
</p>

### scripts
#### ./notebook/
* `Keras_CNN.ipynb`: Classificaiton with CNN by Keras
* `TF_CNN.ipynb`: Classificaiton with CNN by TensorFlow
* `TFslim_Mobilenet.ipynb`: Mobilenet from TF_slim library
#### ./src/
* `Keras_CNN_sample.py`: Classificaiton with CNN by Keras
* `Mobilenet_sample.py`: Classificaiton with CNN by TensorFlow
* `TF_CNN_sample.py`: Mobilenet from TF_slim library
#### ./src/utils/
* `datasets.py`: functions of data load, transoforming data type, normalization, etc.
* `eval.py`: functions for evaluating accuracy of predicted classes
* `visualize.py`: functions of visualizing and saving graph or sample images
#### ./src/nets/
* `tf_CNN.py`: typical layers written in TensorFlow
* `keras_CNN.py`: typical layers written in Keras

## 3. Profiles
### 3.1 Reference
TBD

### 3.2 Requirements
* [Python 3.6.8+](https://www.python.org/)
* [tensorflow 1.10.0 +](https://www.tensorflow.org/)
* [tensorboard 1.12.2 +](https://www.tensorflow.org/guide/summaries_and_tensorboard)
* [keras-gpu 2.2.4+](https://keras.io/)
* [jupyter 1.0.0+](https://jupyter.org/)
* [pandas 0.24.1+](https://pandas.pydata.org/)
* [matplotlib 3.0.2+](https://matplotlib.org/)
* [seaborn 0.9.0+](https://seaborn.pydata.org/)

## 4. Get Started
TBD

### 4.1 Data download
Sample data sets is "EuroSAT"; 10 land cover categories from industrial to permanent crop, 27k 64x64 pixel chips, 3/16 band Sentinel-2 satellite imagery (10m res.), covering cities in 30 countries.
Downloading and unzip "EuroSAT (RGB color space images)" datasets from http://madm.dfki.de/downloads to ~/datasets directory as shown below.

<p>

```
Top
├── datasets                
│   ├── EuroSAT_RGB
│   │   ├── Residential
│   │   ├── Industrial
│   │   ├── HerbaceousVegetation
│   │   ├── PermanentCrop
│   │   ├── AnnualCrop
│   │   ├── Highway
│   │   ├── River
│   │   ├── Forest
│   │   ├── Pasture
│   │   └── SeaLake
...
```
</p>

### 4.3 Training and Validation
TBD

### 4.4 Checking results
TBD