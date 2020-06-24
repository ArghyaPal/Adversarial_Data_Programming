# Getting Started
Please see <a href='https://arghyapal.github.io/ItsArghyaPal.io/minimalist-portfolio-master/ADP_Project_Page.html'> the adversarial data programming website page</a> to make yourself comfortable with the adversarial data programming concept. We will train a basic generative adversarial network (GAN) on MNIST digit dataset - using labeling functions. We will do the following steps:
1. Model a basic generative adversarial network with linear layers
2. We will formalise our Labeling Functions Block using a labeling function based on Kmeans clustering
3. We will train the model end-to-end on MNIST dataset
# Installation
You need to install:
1. Pytorch > 1.2+
2. Python 3.6+
3. matplotlib
4. torchvision
5. install kmeans of pytorch using the command <code>pip install kmeans-pytorch</code>
6. pylab
# Results
The generated images are stored in <code>samples</code> folder. However, you can see the labels after every iteration
# Acknowledgement
The GAN code is based on . And we thank <code>kmeans-pytorch</code> for providing the kmeans unsupervised clustering code.
# How to write labeling functions for real image datasets
You can see <a href='https://github.com/HazyResearch/ukb-cardiac-mri/blob/master/ukb/weak_supervision/coral/tutorials/Intro_Tutorial.ipynb'>the tutorial</a> to write labeling functions for real dataset.
# Citation
If you find the code useful, please cite the paper:<br>
<code>@InProceedings{Pal_2018_CVPR,
author = {Pal, Arghya and Balasubramanian, Vineeth N.},
title = {Adversarial Data Programming: Using GANs to Relax the Bottleneck of Curated Labeled Data},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2018}
}</code>

