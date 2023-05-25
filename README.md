# Machine learning with [`scikit-learn`](https://scikit-learn.org/)

## by [Nayat Sánchez Pi](http://www.nayatsanchezpi.com) and [Luis Martí](http://lmarti.com)

A repository of [Jupyter](https://www.jupyter.org)/[IPython](https://www.ipython.org) notebooks with the slides and code examples for our machine learning course for Sernageomin.

[![Inria](https://img.shields.io/badge/Made%20in-Inria-%23e63312)](http://inria.cl)
[![License: CeCILLv2.1](https://img.shields.io/badge/license-CeCILL--v2.1-orange)](https://cecill.info/licences.en.html)
![Python 3.x](https://img.shields.io/badge/python-3.x-green.svg)
[![nbviwer](https://img.shields.io/badge/view%20in-nbviewer-orange.svg)](http://nbviewer.jupyter.org/github/Inria-Chile/ml-with-sklearn/tree/master/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Inria-Chile/ml-with-sklearn/HEAD)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Inria-Chile/ml-with-sklearn)

## Using the notebooks on the cloud

Open the notebooks in [MyBinder](https://mybinder.org/v2/gh/Inria-Chile/ml-with-sklearn/HEAD) (recommended) or in [Google Colab](https://colab.research.google.com/github/Inria-Chile/ml-with-sklearn).

## Installing locally

- Requirements:
  - Python >=3.8 and <12 and
  - [Poetry dependency manager](https://python-poetry.org).
- Install required libraries (they will go in a `.venv` virtual environment in the current folder).

  ```zsh
  poetry install
  ```

- Activate virtual environment:

  ```zsh
  poetry shell
  ```

- Run notebooks:

  ```zsh
  jupyter notebook
  ```

- Check that all notebooks are working (will take a while):

  ```zsh
  pytest -n=auto --nbmake --nbmake-timeout=600 **/*ipynb 
  ```

## Third-party images and materials usage note

We have made our best to acknowledge the corresponding author whenever using third-party materials. If you find any misattributions do not hesitate to contact us.
