# NLP Analysis Sentiment

Sentiment Analysis using three different frameworks: [Scikit-Learn](https://scikit-learn.org/), [Keras](https://keras.io/), and [PyTorch](https://pytorch.org/). Also, I use [MLFlow](https://mlflow.org/) for tracking model performance for different experiments.

# Python Dependencies

Choose one option below [1](#1-poetry) or [2](#2-virtualenv)

## 1. Poetry

```console
# project root
$ poetry install  # you need to have poetry installed
```

## 2. Virtualenv

```console
$ python -m venv .venv
$ source .venv/bin/activate  # Unix
$ pip install -r requirements.txt
```


```console
$ mlflow server --host 127.0.0.1 --port 8080
```