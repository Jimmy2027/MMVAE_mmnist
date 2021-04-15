# MMVAE_mmnist
[![Build Status](https://travis-ci.com/Jimmy2027/MMVAE_mmnist.svg?branch=main)](https://travis-ci.com/Jimmy2027/MMVAE_mmnist)

Codebase for training multi modal VAEs on the MNIST-SVHN-TEXT dataset.

## Installation

```
git clone git@github.com:Jimmy2027/MMVAE_mmnist.git
cd MMVAE_mmnist
path/to/conda/environment/bin/python -m pip install .
```
This repository depends on the codebase from [MMVAE_base](https://github.com/Jimmy2027/MMVAE_base):
```
git clone git@github.com:Jimmy2027/MMVAE_base.git
cd MMVAE_base
path/to/conda/environment/bin/python -m pip install .
```

For development, install with: 
```
git clone git@github.com:Jimmy2027/MMVAE_mmnist.git
cd MMVAE_mmnist
path/to/conda/environment/bin/python -m pip install -e .

git clone git@github.com:Jimmy2027/MMVAE_base.git
cd MMVAE_base
path/to/conda/environment/bin/python -m pip install -e .
```