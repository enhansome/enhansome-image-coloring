# Awesome Software for Image Coloring with stars

A curated list of awesome AI-powered image coloring frameworks, libraries and software. Inspired by `josephmisiti/awesome-machine-learning`. It's a good idea to explore the GitHub topic as well - [Topic "Image colorization"](https://github.com/topics/image-colorization). In comparison to the awesome list `MarkMoHR/Awesome-Image-Colorization` (which focuses on research papers), I focus on practical open-source software.

## Considerations

Most of the software runs in `Python`, and requires some kind of an AI frameworks (e.g. `Tensorflow`) - which means you may need a GPU with a configured `CUDA` toolkit to run it in a reasonable time.

## Frameworks and libraries

### :snake: Python

#### Tensorflow

* [Automatic Image Colorization](https://github.com/Armour/Automatic-Image-Colorization) ⭐ 171 | 🐛 5 | 🌐 Python | 📅 2022-09-08 - Automatic Image Colorization using TensorFlow based on Residual Encoder Network <http://tinyclouds.org/colorize/>
* [Image Colorization using Convolutional Networks](https://github.com/shekkizh/Colorization.tensorflow) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2018-05-17 - Image colorization using CNNs in tensorflow.
* [Photo Coloring Using End2end CNN based Model!](https://github.com/AbdelrahmanRadwan/photo-coloring) ⭐ 59 | 🐛 2 | 🌐 Python | 📅 2018-07-29 - A Deep Learning based coloring tool, which can color a black-white or gray picture.
* [Image and video colorizer](https://github.com/PrimozGodec/ImageColorization) ⭐ 29 | 🐛 5 | 🌐 Python | 📅 2024-08-02 - Image and video colorizer is package for automatic image and video colorization. Models are already trained.
* [PIC - Probabilistic Image Colorization](https://github.com/ameroyer/PIC) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2018-12-13 - Probabilistic Image Colorization <https://arxiv.org/abs/1705.04258>

#### Tensorflow with GANs

* [Image Colorization with Generative Adversarial Networks](https://github.com/ImagingLab/Colorizing-with-GANs) ⭐ 268 | 🐛 12 | 🌐 Python | 📅 2022-09-05 -
  Grayscale Image Colorization with Generative Adversarial Networks. <https://arxiv.org/abs/1803.05400>
* [Image-colorization-using-CycleGAN](https://github.com/ArkaJU/Image-Colorization-CycleGAN) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2021-05-30 - Colorization of grayscale images using CycleGAN in TensorFlow.

#### Keras

* [Coloring Black and White photos with Neural Networks](https://github.com/emilwallner/Coloring-greyscale-images) ⭐ 1,053 | 🐛 8 | 🌐 Python | 📅 2024-01-22 - Coloring black and white images with deep learning.
* [Image-Colorization](https://github.com/thevarunsharma/Image-Colorization) ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-04-29 - Automatic Image Colorization using a Convolutional Network (U-Net)
* [JadeBlue96](https://github.com/JadeBlue96/Image-Colorization-of-Historical-Paintings) ⭐ 5 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-05-16 - Recolorizing grayscaled historical paintings and photos with Deep Learning using an Autoencoder CNN.
* [Image-Coloring](https://github.com/aman-chauhan/Image-Coloring) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-04-03 - Deep Neural Net for coloring grayscale images using local and global image features

#### Fast.AI

* [DeOldify](https://github.com/jantic/DeOldify) ⚠️ Archived - A Deep Learning based project for colorizing and restoring old images.

#### Caffee

* [Colorful Image Colorization](https://github.com/richzhang/colorization) ⭐ 3,461 | 🐛 59 | 🌐 Python | 📅 2023-11-27 - Automatic colorization using deep neural networks. "Colorful Image Colorization." In ECCV, 2016. <http://richzhang.github.io/colorization/>
* [Interactive Deep Colorization](https://github.com/junyanz/interactive-deep-colorization) ⭐ 2,692 | 🐛 32 | 🌐 Python | 📅 2022-07-29 - Deep learning software for colorizing black and white images with a few clicks. <https://richzhang.github.io/ideepcolor/>

#### PyTorch

* [Interactive Deep Colorization in PyTorch](https://github.com/richzhang/colorization-pytorch) ⭐ 601 | 🐛 15 | 🌐 Python | 📅 2020-06-04 - PyTorch reimplementation of Interactive Deep Colorization <https://richzhang.github.io/ideepcolor/>
* [Colorful Image Colorization PyTorch](https://github.com/Time0o/pytorch-colorful-colorization) ⭐ 49 | 🐛 7 | 🌐 Python | 📅 2021-06-16 - A from-scratch PyTorch implementation of "Colorful Image Colorization" by Zhang et al. created for the Deep Learning in Data Science course at KTH Stockholm.
* [Automatic Image Colorization](https://github.com/kainoj/colnet) ⭐ 41 | 🐛 4 | 🌐 Python | 📅 2024-07-25 - Automatic Image Colorization with Simultaneous Classification – based on "Let there be Color!".
* [Image colorization with GANs](https://github.com/karoly-hars/GAN_image_colorizing) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2020-02-07 - Image colorization with generative adversarial networks on the CIFAR10 dataset.
* [Square-Images-Colorization](https://github.com/done1892/Square-Images-Colorization) ⭐ 1 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-08-30 - Colorization algorithms for images depicting cities squares
* [Colorful Image Colorization](https://github.com/Epiphqny/Colorization) - Pytorch implementation of the paper Colorful Image Colorization <https://arxiv.org/abs/1603.08511>

### C++

* [Beyond Landscapes: An Exemplar-based Image colorization method](https://github.com/saulo-p/Exemplar-Image-Colorization) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2019-01-26 - Exemplar-based Image Colorization method based on superpixel segmentation and classification.

### C\#

* [StyleTransfer-Colorization-SuperResolution](https://github.com/ColorfulSoft/StyleTransfer-Colorization-SuperResolution) ⭐ 46 | 🐛 1 | 🌐 C# | 📅 2021-11-16 - Demonstration implementations of neural network image processing algorithms.

## Language-based colorization

* [SketchySceneColorization](https://github.com/SketchyScene/SketchySceneColorization) ⭐ 105 | 🐛 0 | 🌐 Python | 📅 2021-05-11 - Language-based Colorization of Scene Sketches. (SIGGRAPH Asia 2019) <https://sketchyscene.github.io/SketchySceneColorization/>

## Implementations / apps

### iOS

* [Colorizer iOS](https://github.com/alex011235/Colorizer-iOS) ⭐ 28 | 🐛 2 | 🌐 Swift | 📅 2021-03-01 - Transform grayscale photos to color photos in iOS

## :books: Relevant knowledge, books and papers

* [Awesome-Image-Colorization](https://github.com/MarkMoHR/Awesome-Image-Colorization) ⭐ 1,163 | 🐛 6 | 📅 2026-07-23 - A collection of Deep Learning based Image Colorization and Video Colorization papers.

* [Build a Photo Restoration App with Python](https://www.youtube.com/watch?v=xgQpalRRW3A) - YouTube tutorial from AssemblyAI on how to build a photo restoration app with Python and Flask.

## :dark\_sunglasses: Related awesome lists

* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,070 | 🐛 26 | 🌐 Python | 📅 2026-08-11 - A curated list of awesome Machine Learning frameworks, libraries and software.
* [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 28,778 | 🐛 85 | 📅 2025-05-26 - A curated list of awesome Deep Learning tutorials, projects and communities.
* [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision) ⭐ 11,183 | 🐛 47 | 📅 2023-08-15 - A curated list of deep learning resources for computer vision.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
