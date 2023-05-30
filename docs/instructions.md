# Getting started with neutron imaging tutorial notebooks

## Introduction
This part of the IAEA e-learning package for neutron imaging is implemented using jupyter-notebooks. 
The notebooks are interactive documents with embedded python code. This concept allows you to modify 
the computations and see what happens, you can even try the demonstrated concepts on your own data to see what happens.
Some of the tutorial notebooks are implemented as exercises where you are guided step by step to 
implement your own python code. These notebooks have a solution notebook accompanying them, in which a
solution is presented. You can chose yourself what benefits your learning and your python skills best. 

There are two main approaches to using the tutorial notebooks; by installing jupyter-notebook on your computer or by running the notebooks on Google Colab.
By installing jupyter locally you have the most freedom to work with the material but if you for examply don't want to fill your hard drive with yet another 
software package there is the Colab solution which you try without installing anything locally.

## Run the notebooks using google Colab
Google colab is a platform where you can run notebooks on googles cloud computers without installing anything locally. Just click on the Colab icon and it starts a notebook <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>

## Run the notebooks using jupyter locally
Jupyter is mostly easiest to install through the Anaconda environment which you can download freely. 
By installing it, you have very good starting point for data analysis using python. It includes a large 
collection of packages preinstalled has a packet manager to help you installing more packages if needed. __Note__: anaconda is still not fully implemented on computers with Apple Silicon CPUs. For these, you have to install a package called miniconda and manually install all dependencies. Which is quite some work.

Anaconda can be installed on their [homepage](https://www.anaconda.com/download). Download and install 
the version for your operating system. 

You will also need to install some additional packages:
- ```tifffile``` for reading tiff-files
This can be done either in the anaconda navigator or on the command line
```bash
conda install tifffile
```

### Getting the notebooks
The notebooks are stored in a collection of github repositories and there are different ways to download them:

#### Download zip-files
Download a zip-file containing the repository. This is sufficient if you don't want to update the local copy of the repository.
- [Image analysis](https://github.com/ImagingELearning/ImageProcessing/archive/refs/heads/main.zip)
- [Resolution](https://github.com/ImagingELearning/resolution/archive/refs/heads/main.zip)
- [Quantification from neutron images](https://github.com/ImagingELearning/QuantifyingNeutronImages/archive/refs/heads/main.zip)

Unzip the files and you have all you need to run the tutorials.

#### Clone the repository using git
Requires that you install a tools to work with git but you can easily get the latest version repository without downloadin all data every time.
```bash
git clone https://github.com/ImagingELearning/ImageProcessing.git
git clone https://github.com/ImagingELearning/resolution.git
git clone https://github.com/ImagingELearning/QuantifyingNeutronImages.git
```


