# Machine Learning

## Purpose

The files contained herein are my practical exercises from studying machine
learning. Implementation of the exercises may vary between languages, but is
mainly being exercised with in python3.

## Getting Started

Clone the source

```bash
$ git clone https://github.com/jmarkowski/machine-learning.git
$ cd machine-learning
```

It's typically a good idea to work in a python environment when install packages
so that they don't interfere with your other projects.

Basically, you want to create a virtual environment, activate it, and install
the packages within it. When you're done, you can `deactivate` the environment.

```
$ virtualenv --python=python3 pyenv/
$ source pyenv/bin/activate
(pyenv)
$ pip install -r requirements.txt
...
$ deactivate
```

## Background

Types of machine learning:

* Supervised learning
* Unsupervised learning
* Reinforcement learning

### Supervised Learning

Supervised learning involves us knowing the *right answer* to a problem. We use
the right answers to train a model.

Supervised learning can be divided into *classification* and *regression*
categories.

The goal of classification is to predict categorical labels of new
instances based on past observations. The goal of regression is to generate a
continuous response instance from an observation.

An example of an implementation of a classification learning model would be to
classify between spam and non-spam email.

An example of an implementation of a regression learning model would be
predicting the price of a home based on parameters such as area, home style, and
neighbourhood.

### Unsupervised Learning

Unsupervised learning deals with data of an unknown structure. We can use
unsupervised learning to explore the structure of data to gain meaningful
insights. *Clustering* is an unsupervised learning technique that organizes data
into meaningful subgroups. Clustering is sometimes known as "unsupervised
classification."

### Reinforcemnet Learning

Reinforcement learning involves the development of a system (agent) that
improves its performance based on interactions with the environment. The
feedback from reinforcement learning is a reward.

An example of reinforcement learning is creating a model that learns how to play
the popular brick breaker game (environment) that learns based on points
(rewards).
