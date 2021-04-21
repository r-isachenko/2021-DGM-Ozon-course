# 2021-DGM-Ozon-course

The course is devoted to modern generative models in the application to computer vision. 

We will study 4 main classes of generative models: 
- autoregressive models, 
- latent variable models, 
- normalization flow models, 
- adversarial models. 

Special attention is paid to the properties of various classes of generative models, their interrelationships, theoretical prerequisites and methods of quality assessment.

The aim of the course is to introduce the student to widely used advanced methods of deep learning.

The course is accompanied by practical tasks that allow you to understand the principles of the considered models.

## Course materials

| Lecture | Date | Description | Lecture | Seminar | 
|---------|------|-------------|--------|--------|
| 1 | February, 11 | Logistics. Motivation. Autoregressive models (MADE, WaveNet, PixelCNN, PixelCNN++). | [slides](lectures/lecture1/Isachenko2021DeepGenerativeModels1.pdf) | [slides](seminars/seminar1/seminar1.ipynb) | 
| 2 | February, 18 | Bayesian Framework. Latent Variable Models. Variational lower bound. EM-algorithm. | [slides](lectures/lecture2/Isachenko2021DeepGenerativeModels2.pdf) | [slides](seminars/seminar2/seminar2.ipynb) | 
| 3 | February, 25 | ELBO, Reparametrization trick, Variational Autoencoder. MLE vs MAP. VAE drawbacks. | [slides](lectures/lecture3/Isachenko2021DeepGenerativeModels3.pdf) | [slides](seminars/seminar3/seminar3.ipynb) | 
| 4 | March, 5 | Mean-field approximation and EM-algorithm. Flow models definition. Forward and reverse KL divergence. | [slides](lectures/lecture4/Isachenko2021DeepGenerativeModels4.pdf) | [slides](seminars/seminar4/seminar4.ipynb) | 
| 5 | March, 11 | Flow models (Planar flows, NICE, RealNVP, Glow). Flows in variational inference. | [slides](lectures/lecture5/Isachenko2021DeepGenerativeModels5.pdf) | [slides](seminars/seminar5/seminar5.ipynb) | 
| 6 | March, 18 | Autoregressive flows (MAF, IAF). Flow KL duality. Uniform dequantization. | [slides](lectures/lecture6/Isachenko2021DeepGenerativeModels6.pdf) | [slides](seminars/seminar6/seminar6.ipynb) |  
| 7 | March, 25 | Variational dequantization. IWAE. ELBO surgery. | [slides](lectures/lecture7/Isachenko2021DeepGenerativeModels7.pdf) | [slides](seminars/seminar7/seminar7.ipynb) | 
| 8 | April, 1 | VampPrior + Autoregressive prior. Posterior collapse. Disentanglement learning (beta-VAE). | [slides](lectures/lecture8/Isachenko2021DeepGenerativeModels8.pdf) | [slides](seminars/seminar8/seminar8.ipynb) | 
| 9 | April, 8 | Disentanglement learning (DIP-VAE + summary). Likelihood-free learning. GAN theorem. | [slides](lectures/lecture9/Isachenko2021DeepGenerativeModels9.pdf) | [slides](seminars/seminar9/seminar9.ipynb) | 
| 10 | April, 15 | Gan problems: vanishing gradients + mode collapse. KL vs JSD. DCGAN. Wasserstein GAN. | [slides](lectures/lecture10/Isachenko2021DeepGenerativeModels10.pdf) | [slides](seminars/seminar10/seminar10.ipynb) | 
| 11 | April, 22 | WGAN-GP. Spectral Normalization GAN. f-divergence minimization. GAN evaluation (Inception score, FID) | [slides](lectures/lecture11/Isachenko2021DeepGenerativeModels11.pdf) | [slides](seminars/seminar11/seminar11.ipynb) | 

## Homeworks 
| Homework | Date | Deadline | Description | Link |
|---------|------|-------------|--------|-------|
| 1 | February, 11 | February, 28 | Hostogram + MADE (practice). | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/homework1/hw1.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-Ozon-course/blob/main/homeworks/homework1/hw1.ipynb)|
| 2 | February, 28 | March, 14 | Autoregressive models + LVM (theory). | [pdf](homeworks/homework2/hw2.pdf) |
| 3 | March, 14 | March, 28 | VAE + RealNVP (practice). | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/homework3/hw3.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-Ozon-course/blob/main/homeworks/homework3/hw3.ipynb)|
| 4 | March, 28 | April, 11 | AR flow + VAE with AR prior (practice). | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/homework4/hw4.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/r-isachenko/2021-DGM-Ozon-course/blob/main/homeworks/homework4/hw4.ipynb)|
| 5 | April, 11 | April, 25 | Sylvester Flow + ELBO MI + IW dequantization + LSGAN (theory). | [pdf](homeworks/homework5/hw5.pdf) |
