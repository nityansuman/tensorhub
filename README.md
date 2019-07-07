# TensorHub [![Codacy Badge](https://api.codacy.com/project/badge/Grade/04448209352a4ad0a7c4e7fcf09977ef)](https://www.codacy.com/app/nityansuman/tensorhub?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nityansuman/tensorhub&amp;utm_campaign=Badge_Grade)

<img alt="PyPI" src="https://img.shields.io/pypi/v/tensorhub.svg?color=blue&style=for-the-badge"> <img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/tensorhub.svg?style=for-the-badge">  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/nityansuman/tensorhub.svg?color=blue&style=for-the-badge"> <img alt="PyPI - License" src="https://img.shields.io/pypi/l/tensorhub.svg?style=for-the-badge">


## You have just found TensorHub.

The open source library to help you develop and train ML models, easy and fast as never before with `TensorFlow 2.0`.
`TensorHub` is a global collection of `building blocks` and `ready to serve models`.

It is a wrapper library of deep learning models and neural lego blocks designed to make deep learning more accessible and accelerate ML research.


Use `TensorHub` if you need a deep learning library that:

+ **Reproducibility** - Reproduce the results of existing pre-training models (such as Google BERT, XLNet)

+ **Model modularity** - TensorHub divided into multiple components: ready-to-serve models, layers, neural-blocks etc. Ample modules are implemented in each component. Clear and robust interface allows users to combine modules with as few restrictions as possible.

+ **Prototyping** - Code less build more. Apply `TensorHub` to create fast prototypes with the help of modulear blocks, custom layers, custom activation support.

+ **Platform Independent** - Supports both `Keras` and `TensorFlow 2.0`. Run your model on CPU, single GPU or using a distributed training strategy.


## Available on PyPI
```
pip install tensorhub
```

![TensorHub](data/header.png)

*Next Pre-Release: v1.0alpha3 --> 7th July 2019*


**Quickstart Guide**

+ [Learn TensorFlow 2.0](examples/)
+ [Text Classifier Example](examples/run_text_classifiers.py)

## Coming in TensorHub v1.0
+ Cooked Models
    + Image Classification (Supports Transfer Learning with ImageNet Weights)
        + Xception
        + VGG16
        + VGG19
        + ResNet50
        + InceptionV3
        + InceptionResNetV2
        + MobileNet
        + DenseNet
        + NASNet

    + Text Classification
        + RNN, LSTM, GRU Based Model
        + Text-CNN
        + *More under planning...*

    + Neural Machine Translation
        + Encoder-Decoder Standard Sequence Model (Encoder, Decoder -> [RNN, LSTM, GRU])
        + Translation with Attention

    + Text Generation
        + RNN, LSTM, GRU Based Model
    
    + Named Entity Recogniton
        + RNN, LSTM, GRU Based Model

+ Layers
    + Standard
        + Linear
        + *More under planning...*
    + Attention
        + Bahdanau Attention
        + Luong Attention
        + Self-Attention

+ Activations
    + RELU
    + SELU
    + GELU
    + ELU
    + Tanh
    + Sigmoid
    + Hard Sigmoid
    + Softmax
    + Softplus
    + Softsign
    + Exponential
    + Linear

+ Utilities
    + Text
        + Custom Tokenizer
        + Load Embeddings
        + *More under planning...*
    + Image
        + *Under planning...*


## Why TensorFlow
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

**Easy model building**
Build and train ML models easily using intuitive high-level APIs like Keras with eager execution, which makes for immediate model iteration and easy debugging.

**Robust ML production anywhere**
Easily train and deploy models in the cloud, on-prem, in the browser, or on-device no matter what language you use.

**Powerful experimentation for research**
A simple and flexible architecture to take new ideas from concept to code, to state-of-the-art models, and to publication faster.

**[Install TensorFlow and Get Started!](https://www.tensorflow.org/install)**

**[Build, deploy, and experiment easily with TensorFlow](https://www.tensorflow.org/)**


## Let's Work Together

We are eager to collaborate with you. Feel free to open an issue on or send along a pull request.
If you like the work, show your appreciation by "FORK", "STAR", or "SHARE".

[![Love](https://forthebadge.com/images/badges/built-with-love.svg)](https://GitHub.com/nityansuman/tensorhub/)