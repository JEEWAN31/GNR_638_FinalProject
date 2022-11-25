# About The Project

This repository contains our course project `Neural_Super_Sampling` of `GNR638` course `Machine Learning for Remote Sensing- Part 2`  done under prof. `Biplab Banerjee` in our Autumn 2022 at IIT Bombay. 

## Team Mates

* Jeewan Chandra Joshi (200020063)
* Ajinkya Bobde (200040014)
* Tanisha Gupta (200100155)

# GNR_638_FinalProject
SRGAN is a generative adversarial model for super-resolution. Despite the breakthroughs in accuracy and speed of single image super-resolution using faster and deeper convolutional neural networks, one central problem remains largely unsolved: how do we recover the finer texture details when we super-resolve at large upscaling factors?

![](https://github.com/JEEWAN31/GNR_638_FinalProject/blob/main/Images/Screenshot%202022-11-24%20at%201.42.05%20PM.png)


### ESRGAN

The main architecture of the ESRGAN is the same as the SRGAN with some modifications  ESRGAN follows the baseline ResNet-style architecture of SRGAN but replaces the residual block with the RRDB block. The RRDB block is inspired by the DenseNet architecture and connects all layers within the residual block directly with each other(see the right figure). We can implement the RRDB block similar to DenseNet by feeding the concatenated array of the output of every previous layer to the next convolution. The following code implements the RRDB block.

![COmparing super resolutioni with all GAN models](https://github.com/JEEWAN31/GNR_638_FinalProject/blob/main/Images/Screenshot%202022-11-24%20at%201.43.22%20PM.png)

## Resources:

Link of Dataset Used: [LINK](https://drive.google.com/drive/folders/1o6Do6HiqyFx6BxUQVzsAGp7AJhwGMndf?usp=sharing)

Link of PPT: [LINK](https://docs.google.com/presentation/d/1exqaWnUl85NDd8ykS5atLwKjNKVvFJLb/edit?usp=sharing&ouid=113817239763706000380&rtpof=true&sd=true)

Medium Article Link : [LINK](https://medium.com/@jeewanjj02/esrgan-srgan-image-resolution-using-deep-learning-b013f27254a0)

Link of Video: [LINK](https://drive.google.com/file/d/13KisbUx0cYLKUZu2MWQl78lzF1x9moc7/view?usp=sharing)

## Bibliography:

Original papers:
SRGAN :[ Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network ](https://openaccess.thecvf.com/content_cvpr_2017/papers/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.pdf) CVPR_2017

ESRGAN : [ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Wang_ESRGAN_Enhanced_Super-Resolution_Generative_Adversarial_Networks_ECCVW_2018_paper.pdf)


1. https://www.youtube.com/watch?v=nbRkLE2fiVI
2. https://www.youtube.com/watch?v=1HqjPqNglPc&t=492s
3. https://www.mdpi.com/2072-4292/12/8/1263
4. https://github.com/fenghansen/ESRGAN-Keras
5. https://github.com/sudoRicheek/Image-Enhancer


