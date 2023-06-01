# cvrmap-paper

Jupyter notebook to generate the figures from the cvrmap paper

## Introduction

CVRmap is an opensource BIDS app to compute maps or Cerebro-Vascular Reactivity (CVR) from fMRI data. The repository for the actual code of CVRmap is located here: `github.com/ln2t/cvrmap`. In this repository, we include the jupyter notebooks used to generate the figures of the paper presenting `cvrmap`.

## Instructions for use

To use the scripts in this repository, you must first download the data processed using CVRmap. This can be done here: `openneuro.org/dsXXXX`.
The location of the downloaded data must be used in the jupyter notebook. Moreover, make sure you have all python dependencies installed. This notebook uses the following packages:

```
pandas
numpy
scipy
matplotlib
plotly
pybids
nibabel
nilearn
```

## Bugs or questions

Do not hesitate to open an issue if you find bugs or if you have questions.
