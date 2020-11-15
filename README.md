## Tensorflow

This module contains articles about Tensorflow

## Relevant articles:

- [Introduction to Tensorflow for Java](https://www.baeldung.com/tensorflow-java)

## How to install TensorFlow-1.15 and python-3.7 
    Python=3.7 and Tensorflow=1.15
    
    ==> For Tensorflow legacy-java api <==
    <groupId>org.tensorflow</groupId>
    <artifactId>tensorflow</artifactId>
    <version>1.15</version>
    ======================================
    
    Download and install Anaconda- V3
    Install Anaconda pkg files.
    Update .bash_profile and .zshrc
    ~>$ source ~/.bash_profile 
    ~>$ conda --version
    
    ~>$ conda create -n ocr_env python=3.7
    ~>$... Install-Start
    ~>$... Done
    
    ~>$ conda activate ocr_env
    
    ##Now install tensorflow=1.15 with others
    #
    ~>$ pip install tensorflow==1.15 lxml pillow matplotlib jupyter contextlib2 cython tf_slim
    ...
    ...
    ...
    ... Done & successful
    
    ~>$ pip show tensorflow
    Name: tensorflow
    Version: 1.15.0
    Summary: TensorFlow is an open source machine learning framework for everyone.
    Home-page: https://www.tensorflow.org/
    Author: Google Inc.
    Author-email: packages@tensorflow.org
    License: Apache 2.0
    Location: /Users/towhidulislam/Documents/applications/anaconda/anaconda3/envs/ocr_env/lib/python3.7/site-packages
    Requires: tensorboard, tensorflow-estimator, protobuf, absl-py, termcolor, opt-einsum, six, astor, numpy, gast, wheel, keras-preprocessing, wrapt, google-pasta, keras-applications, grpcio
    Required-by:
    
    ~>$ brew install protobuf
    ~>$ ... Done and Successful 
