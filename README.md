<p align="center"><img src="metadata/th-logo.png?raw=true" alt="LOGO"/></p>

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/92d9bc37335c4fda8bedb50455ef1233)](https://app.codacy.com/manual/nityansuman/tensorhub?utm_source=github.com&utm_medium=referral&utm_content=nityansuman/tensorhub&utm_campaign=Badge_Grade_Settings)
![GitHub LICENSE](https://img.shields.io/github/license/nityansuman/tensorhub)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/nityansuman/tensorhub)
![GitHub repo size](https://img.shields.io/github/repo-size/nityansuman/tensorhub)
![GitHub language count](https://img.shields.io/github/languages/count/nityansuman/tensorhub)

![GitHub last commit](https://img.shields.io/github/last-commit/nityansuman/tensorhub)
![Maintenance](https://img.shields.io/maintenance/yes/2020)

## You have just found TensorHub!

TensorHub is a library built on top of TensorFlow 2.0. It is designed to provide simple, modular and repeatable abstractions to accelerate machine learning research. TensorHub is also designed to be simple to understand, easy to write and quick to change (according to the need of the hour!).

Unlike many frameworks TensorHub is extremely flexible about how to use modules. Modules are designed to be self contained and entirely decoupled from one another. TensorHub does not ship with a training framework and users are encouraged to build their own or adopt those built by others. In future training framework and inference engine would also be part of TensorHub build on top of an already amazing peace of art (heard about ML-Flow!).


Use TensorHub if you need a deep learning library that:
+ **Reproducibility** - Reproduce the results of existing pre-training models (such as ResNet, VGG, BERT, XLNet).

+ **Modularity** - Clear and robust interface allows users to combine modules with as few restrictions as possible.

+ **Fast** - Our custom utilities and layers are made from the ground up to support pre-existing standard frameworks like TensorFlow and Keras with efficiency in mind.

+ **Prototyping** - Code less build more. Apply modular blocks to create fast prototypes with the help of pre-cooked models, custom layers and utilities support.

+ **Platform Independent** - Run your model on CPU, single GPU or using a distributed training strategy on top of TensorFlow 2.0.

## Getting started: 30 seconds to TensorHub

Building a question answering system, an image classification model, a Neural Turing Machine, or any other model is just as fast.
The ideas behind deep learning are simple, so why should their implementation be painful?

For a more in-depth tutorial (coming up!), you can check out:

+ [Getting started with Text Classification](https://github.com/nityansuman/tensorhub/tree/master/examples/getting-started-with-text-classification.ipynb)
+ [Getting started with Image Classification](https://github.com/nityansuman/tensorhub/tree/master/examples/getting-started-with-image-classification.ipynb)

## Installation

To get started install TensorFlow 2.0 and TensorHub:

```
$ pip install tensorflow
$ pip install tensorhub
```

You can run the following to verify things installed correctly:

```
import tensorflow as tf
import tensorhub as th

print("TensorFlow version {}".format(tf.__version__))
print("TensorHub version {}".format(th.__version__))
```

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Love](https://forthebadge.com/images/badges/built-with-love.svg)](https://GitHub.com/nityansuman/tensorhub/)
