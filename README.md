# cvrmap-paper

Jupyter notebook to generate the figures from the cvrmap paper. Also showcase very simple group-level analysis.

## Introduction

`cvrmap` is an opensource BIDS app to compute maps of Cerebro-Vascular Reactivity (CVR) from fMRI data. The repository for the actual code of `cvrmap` is located here: `github.com/ln2t/cvrmap`. In this repository, we include the jupyter notebook used to generate the figures of the paper presenting `cvrmap` (DOI to come).

## Instructions for use

To use the notebook, you must first download the data processed using `cvrmap`. This can be done here: `openneuro.org/ds004604` (select version v1.0.0). Make sure you have downloaded the `cvrmap` derivatives for all subjects (50) from the dataset.
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
