# ICME Deep Learning Workshop
This repository hosts the ipython notebooks used for the Deep Learning workshop hosted by the [Institute for Computational and Mathematical Engineering at Stanford University](icme.stanford.edu)

## Instructions and installation
Running the notebooks requires a working installation of python 2.7 with tensorflow and jupyter notebooks installed.

The easiest way to install the dependencies is to get the anaconda distribution of python from [Anaconda](https://www.continuum.io/downloads)

Then Tensorflow can be installed by executing
```
pip install tensorflow
```
using the python package manager pip.

If you already have python or do not wish to use anaconda, visit the [Tensorflow website](https://www.tensorflow.org/install/) to find the relevant install instructions for your operating system. Jupyter notebooks can be installed using instructions from the [Jupyter website](http://jupyter.readthedocs.io/en/latest/install.html)

## Running the notebooks
The notebooks can be run by navigating to this directory with your shell/command window and executing
```
jupyter notebook
```
If everything is installed correctly this should open a jupyter project page with a list of the notebooks in your browser.

### Running the computer vision notebook
For the computer vision notebook you need to download the [CIFAR10 data](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) and extract it into this directory.

Alternatively you can run the shell script `get_data.sh` and extract the downloaded archive

### Running the NLP notebook
For the NLP notebook you need to download the [Cornell movie dialogue data](www.mpi-sws.org/~cristian/data/cornell_movie_dialogs_corpus.zip) and extract it into this directory
