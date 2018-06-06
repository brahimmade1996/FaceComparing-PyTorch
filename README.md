# FaceComparing-PyTorch
For my final year project, I did a little project about Face Comparing. I seperately used 2 metric learning algorithms(Siamese CNN and Triplet CNN) in it. 

## Requirements
Python 3.6 is required.

The project is based on PyTorch 0.3.1, with Torchvision 0.2.0. If u want to run it under the newest 0.4.0(launched in late April), there should be some modifications yet to be done.   

Also, the whole project was written on Jupyter Notebook.  

For the above, I recommand using *Anaconda* to set up the environment.

## Datasets
Any dataset can be used, as long as u make sure that each class is in its own folder. 

In my project, i used AT&T dataset and two LFW-related datasets which i modified from LFW-crop and LFW-a.

## Online Triplet Mining
See [this](https://omoindrot.github.io/triplet-loss#batch-hard-strategy).

As the Triplet CNN model is hard to converge by randomly choosing the triplets, I did 3 different ways to do the online mining(Batch-all,batch-hard and batch semi-hard).

Also i had a little try on a mixed-strategy, that is using Batch-All at the beginning and then Batch-Hard to train the model.

## Code structure
*Face Comparing by Siamese Network.ipynb* is a Siamese CNN model for face comparing, including the training, validation and testing.

*Triplet CNN Batch-All Batch-Semi-Hard.ipynb* and *Triplet CNN Batch-Hard.ipynb* are Triplet CNN models with different Online Triplet Mining strategies.

The *Triplet CNN Software.ipynb* is the testing part of those Triplet CNN models above(results are based on the Mixed-Strategy). 

## Pre-trained Models
I will later upload them onto my Baidu NetDisk.
