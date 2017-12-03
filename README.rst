======================================
Tensor methods in Python with TensorLy
======================================

This repository contains a series of tutorials and examples on tensor learning, with implementations in Python using `TensorLy <https://github.com/tensorly/tensorly>`_, and how to combine tensor methods and deep learning using the `MXNet <https://mxnet.incubator.apache.org/>`_ and `PyTorch <http://pytorch.org/>`_ backends.


Installation
============
You will need to have the latest version of TensorLy installed to run these examples as explained in the `instructions <https://tensorly.github.io/dev/installation.html>`_.

The easiest way is to clone the repository::

   git clone https://github.com/tensorly/tensorly
   cd tensorly
   pip install -e .


Then simply clone this repository::

   git clone https://github.com/JeanKossaifi/tensorly_notebooks


You are ready to go!

Table of contents
=================

1 - Tensor basics
-----------------

- `Manipulating tensors (unfolding, n-mode product, etc) <https://github.com/tensorly/tensorly-notebooks/blob/master/01_tensor_basics/tensor_manipulation.ipynb>`_

2 - Tensor decomposition
------------------------

- `CP decomposition <https://github.com/tensorly/tensorly-notebooks/blob/master/02_tensor_decomposition/cp_decomposition.ipynb>`_
- `Tucker decomposition <https://github.com/tensorly/tensorly-notebooks/blob/master/02_tensor_decomposition/tucker_decomposition.ipynb>`_

3 - Tensor regression
---------------------

- `Low-rank tensor regression <https://github.com/tensorly/tensorly-notebooks/blob/master/03_tensor_regression/Low_rank_tensor_regression.ipynb>`_

4 - Tensor methods and deep learning with the MXNet backend
-----------------------------------------------------------

- `Tucker decomposition via gradient descent <https://github.com/tensorly/tensorly-notebooks/blob/master/04_mxnet_backend/tucker_decomposition_with_mxnet_and_tensorly.ipynb>`_
- `Tensor regression networks <https://github.com/tensorly/tensorly-notebooks/blob/master/04_mxnet_backend/tensor_regression_layer_MXNet.ipynb>`_

5 - Tensor methods and deep learning with the PyTorch backend
-------------------------------------------------------------

- `Tucker decomposition via gradient descent <https://github.com/tensorly/tensorly-notebooks/blob/master/05_pytorch_backend/tucker_decomposition_tensorly_and_pytorch.ipynb>`_
- `Tensor regression networks <https://github.com/tensorly/tensorly-notebooks/blob/master/05_pytorch_backend/tensor_regression_layer_pytorch.ipynb>`_

Useful resources
=================

The following are very useful sources of information and I highly recomment you check them out:

- `TensorLy documentation <https://tensorly.github.io/dev/index.html>`_ : extensive documentation, API, etc.
- `Deep Learning - The Straight Dope <https://github.com/zackchase/mxnet-the-straight-dope>`_ : a great tutorial for Deep Learning using MXNet, by Zack Lipton.
- `Deep Learning with PyTorch <http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html>`_ : another great tutorial, this time with PyTorch, by Soumith Chintala. 
