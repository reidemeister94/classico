# Job Categorizer

Classification model for job openings written in **Keras**, composed of _Convolutional Neural Net_ for sentence embedding creation ([universal-sentence-encoder-multilingual](https://tfhub.dev/google/universal-sentence-encoder-multilingual/3)) + dense layers for classification.

## Prerequisites

- Python 3.9+

- pip/virtualenv/conda installed

## Installing Requirements

Create a virtualenv and install requirements. You can do this by running:

```bash

virtualenv venv

source venv/bin/activate

pip install -r requirements.txt

```

## Train and Evaluate Model

After the installation of the requirements, it is possible to run the `training.ipynb` notebook placed in the root of the project, where everything needed for training and evaluation is included.
