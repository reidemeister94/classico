# CLASSICO
## A multilingual Job Categorizer

Multi-language classification model for job openings written in **Keras**, composed of [_Convolutional Neural Net_](https://tfhub.dev/google/universal-sentence-encoder-multilingual/3) for sentence embedding creation + dense layers for classification.

## Prerequisites

- Python 3.8+

- pip/virtualenv/conda installed

## Installing Requirements

Create a virtualenv and install requirements. You can do this by running:

```bash

virtualenv venv --python=python3.8

source venv/bin/activate

pip install -r requirements.txt

```

## Train and Evaluate Model

After the installation of the requirements, it is possible to run the `training.ipynb` notebook placed in the root of the project, where everything needed for training and evaluation is included.
