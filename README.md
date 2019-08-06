# Deep Learning with PyTorch

This repo contains notebooks and related code for Udacity's Deep Learning with PyTorch lesson. This lesson appears in our [AI Programming with Python Nanodegree program](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089).

* **Part 1:** Introduction to PyTorch and using tensors
* **Part 2:** Building fully-connected neural networks with PyTorch
* **Part 3:** How to train a fully-connected network with backpropagation on MNIST
* **Part 4:** Exercise - train a neural network on Fashion-MNIST
* **Part 5:** Using a trained network for making predictions and validating networks
* **Part 6:** How to save and load trained models
* **Part 7:** Load image data with torchvision, also data augmentation
* **Part 8:** Use transfer learning to train a state-of-the-art image classifier for dogs and cats

----

## Dependencies

To run these notebooks you'll need to install Python 3.6+, PySyft, Numpy, PyTorch 1.0, and Jupyter Notebooks. The easiest way for all of this is to create a conda environment:

```bash
conda create -n pysyft python=3
conda activate pysyft
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch
pip install syft
```
