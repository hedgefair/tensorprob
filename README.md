# TensorProb

A probabalistical graphical modeling framework based on [TensorFlow](https://github.com/tensorflow/tensorflow).

TensorProb is a library that allows you to construct complex probility distributions
from primitive ones and perform inference on data.

Posterior distribution or Likelihood function are constructed and evaluated using TensorFlow,
which means your model can automatically be evaluated on multiple CPU cores and GPUs.
This also makes it very easy to add new custom probability distributions, or to
debug your model if it's not doing what you expect.
