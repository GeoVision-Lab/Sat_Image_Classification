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
TBD

## 4. Get Started
TBD

### 4.1 Data download
TBD

### 4.3 Training and Validation
TBD

### 4.4 Checking results
TBD