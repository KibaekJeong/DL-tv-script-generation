# Deep Learning - TV Script Generation

## Table of Contents
- [Overview](#Overview)
- [Dependencies](#Dependencies)
- [Data](#Code)
- [Running the code](#Running-the-code)
- [Data](#Data)

## Overview
In following project, Recurrent Neural Network (RNN) will be utilized to create TV scripts. Seinfeld scripts will be used as dataset. Recurrent Neural Network is built with Pytorch in this project. RNN is trained to learn patterns in training data and generate fake TV script.

## Dependencies

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pytorch](http://https://pytorch.org/)


You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.


## Data
In following project, [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv), provided from [Kaggle](https://www.kaggle.com/), is used for training the model.

## Sample Output
```
bookman: i don't want any money.

peterman: you know, it's a little adjustment.

hoyt: and you were going to the movies.

[new 1: i don't know what this country's is.

george: what?

george:(pointing around) : hey, what are you doin'?

elaine: well, i don't want you to come to the bathroom and forth)

hoyt: you know...
```
