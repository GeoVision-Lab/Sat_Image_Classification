# Satellite Image classification with TensorFlow and Keras

CNN for multi-class image classification in TensorFlow and Keras

## 1. Structure of directories
### sub directories
<p>

```
Top
├── datasets            :locate datasets
│   └── EuroSAT_RGB     :download and unzip sample data
├── notebook            :Jupyter notebooks for users' understanding
│   └── nets            :Models in TF and Keras for the Jupyter notebooks
├── src                 :Python code for execute classification
│   ├── nets            :Models in TF and Keras
│   │   └──tfslim_nets  :Forked from tf_slim library
│   └──utils            :help functions
├── tensorboard         :output from calculation by each codes 
│   ├── keras_cnn       :result of /src/Keras_CNN_sample.py
│   ├── slim_mobilenet  :result of /src/Mobilenet_sample.py
│   └── tf_cnn          :result of /src/TF_CNN_sample.py
...
```
</p>

