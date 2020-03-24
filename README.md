# Adversarial-Training-on-MNIST-Dataset
This repository code for attacks and defenses implemented for Predictx 2019 - A Deep Learning Competition

A CNN model was trained on Clean images from the mnist dataset and tested on the clean test set which resulted in a 99% + accuracy.
The same model when tested on adversarial images crafted by the PGD attack proposed by Madry et. al. in ICLR 2018 resulted in a very poor accuracy.
Hence this model was trained on these adversarial images to make it robust to adversarial attacks like PGD,FGSM and I-FGSM. resulting in a 96% + accuracy when tested on adversarial images.

1. The notebook is implemented in PyTorch.
2. This notebook is my submission for the Predictx 2019 competition which fetched me the runners up position.
3. The starter code for this notebook was provided by the contest organizers.

References:
1. Towards Deep Learning Models Resistant to Adversarial Attacks- Madry et. al in ICLR 2018
2. Explaining and Harnessing Adversarial Examples- GoodFellow et. al 2014

