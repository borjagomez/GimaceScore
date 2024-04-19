# Feline Grimace Scale

This repository implements the training of a CNN to detect cat face features. These
features will be used to infer the Grimace Scale with a NN.

Both CNN and NN are yet to be defined.

## Dataset

The original dataset comes from Kaggle: https://www.kaggle.com/datasets/crawford/cat-dataset/data
It's stored at data/dataset

There are 1,7K images with it's corresponding annotation file (.cat). It provides
coordinates for the different elements of the picture:

- Number of points (default is 9)
- Left Eye
- Right Eye
- Mouth
- Left Ear-1
- Left Ear-2
- Left Ear-3
- Right Ear-1
- Right Ear-2
- Right Ear-3
