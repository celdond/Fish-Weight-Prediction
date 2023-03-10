# Fish Weight Prediction

A Linear Regression model to predict the weight of a fish based on its characteristics.

## Overview

Weight is an important metric to guage fish by for humans as it corresponds to the value
of the fish in terms of being a product.  Weight also serves as one of many references
to the health of living organisms.  The goal of this trained model is to estimate
the weight of a fish based on input characteristics detailed below.

## Project Description

The files in this project:

- Fish.csv:             The data set to be used in the project.
- prediction.ipynb:     A Jupyter Notebook housing the core of the code.
- requirements.txt:     The python requirements file for local use

prediction.ipynb contains the best model as well as four lesser working models for reference.
Every model uses either Ridge or Linear Regression as decribed by the Sci-kit library.

The data set includes the following species of fish: Bream, Roach, Whitefish, Parkki, Perch,
Pike, and Smelt.  The fundamental flaw of this data set is its size - exacerbated by the variety
of fish with in.  It is too small for the number of species there are with in it.  This is why the
best model opts to disregard these categories.

## Use and Install

This project was coded on a local machine using Python 3.10.7 and the packages described
in the included requirements.txt.  To mimic this environment, simply clone said repository
on a local machine and run the following python command in your desired location.

pip install -r requirements.txt

This project used a virtual environment.

As a Jupyter Notebook, web applications such as Google Colab will be a servicable alternative,
and the project should work fine as long as the data is loaded in appropriately.

Data is included in the repository for ease and its small size.
