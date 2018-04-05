# accelerated_dl_pytorch
This is the repository for **Accelerated Deep Learning with Pytotch** tutorial and [**Jupyter Day Atlanta 2018**](https://github.com/atl-jugheads/jupyter-day-atlanta-ii) talk slides. It features full tutorial notebook, Jupyter Notebook Slides html file, and a demo with surface finish quality inspection.

## Knowledge Prerequisites
This tutorial assumes familiarity with Python and Numpy.

## Tutorial Prerequisites
Python3 is required to run this tutorial. You also will need some libraries from SciPy package (NumPy, Matplotlib, Pandas), Jupyter Notebook support, Seaborn for plotting, and Pytorch 0.3.0 or newer.

The simpliest way to maintain Python with all these libraries as well as many others is to install [Anaconda](https://www.anaconda.com/download). You can Find Pytorch installation instructions on the [Pytorch page](http://pytorch.org).

CUDA availability is not strictly required, but highly desirable. Life is short -- use a GPU!

## How to Use
Our tutorial git has two submodules - for surface dataset, and for pretrained model for surface finish quality inspection. To download the tutorial, use 

```
git clone --recurse-submodules git@github.com:hpcgarage/accelerated_dl_pytorch.git
```

If you didn't clone repository with its submodules, you can always clone submodules with this command:

```
git submodule update --init --recursive
```

To run the Jupyter Notebook Slides as at Jupyter Day Atlanta 2018 talk, you can use following command:

```
jupyter nbconvert tutorial_presentation.ipynb --to slides --post serve
```

## Table of Contents
1. Essential PyTorch Background
2. PyTorch for Data Analytics
3. LeNet Convolutional Neural Network (CNN) in PyTorch
4. Application to a Manufacturing Problem

