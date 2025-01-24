# Introduction

- [Introduction Slides](https://docs.google.com/presentation/d/1JzMMtg9QbRyOsE14DsPpDvONBW3-dHS7o11HLDj5T2c/edit?usp=sharing)
- [Example Sketches](https://editor.p5js.org/ml_4_cc/collections/bUBxPzueE)

## Objectives

- Define Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL).
- Overview of applications of machine learning, especially for art and design.
- Learn about the tools for machine learning.
- Understand the difference between classification and regression.
- What is a “[pre-trained model](https://docs.ml5js.org/#/learn/ml5-glossary?id=pretrained-model)”?
- Understand what [ml5.js](https://ml5js.org/about/) is and how it fits into the TensorFlow and open source machine learning library ecosystem.
- Learn how to create an image classifier with ml5.js and [MobileNet](https://docs.ml5js.org/#/learn/ml5-glossary?id=mobilenet).
- Understand how the MobileNet model was trained, specifically the origins and collection methodology for the training.
- Distinguish between a “feature vector” (aka logits) and the last layer (aka softmax probabilities) of a classification network.
- Understand the process of “transfer learning”.

### Tools

- [p5.js](https://p5js.org)
- [ml5.js](https://ml5js.org)
- [TensorFlow.js](https://www.tensorflow.org/js)
- [Teachable Machine](https://teachablemachine.withgoogle.com)

### Code Examples

- [Image Classification - Single Image](https://editor.p5js.org/ml_4_cc/sketches/D71CzHMXL)
- [Image Classification - Drag and Drop Image](https://editor.p5js.org/ml_4_cc/sketches/Y8fFLERev)
- [Image Classification - Video](https://editor.p5js.org/ml_4_cc/sketches/-Sr0UJPKC)
- [Image Classification - Video with Speech Output](https://editor.p5js.org/ml_4_cc/sketches/wDgNVJPKx)
- [ml5.js + Teachable Machine Video Example](https://editor.p5js.org/ml_4_cc/sketches/UeAjLnXQz)

### ml5.js Video Tutorials

- [A Beginner's Guide to Machine Learning with ml5.js - video tutorial](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/0-introduction/1-introduction) (_This video does not reference ml5.js 1.0, refer to the [ml5.js Resources Wiki page](https://github.com/ml5js/Intro-ML-Arts-IMA-F24/wiki/ml5.js-Resources#ml5js-10-resources) for more information._)
- [ml5.js: Image Classification](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/1-classification/image-classification)
- [Teachable Machine video tutorials](https://thecodingtrain.com/tracks/teachable-machine) (_These videos do not reference ml5.js 1.0, refer to the [ml5.js Resources Wiki page](https://github.com/ml5js/Intro-ML-Arts-IMA-F24/wiki/ml5.js-Resources#ml5js-10-resources) for more information._)

## Supplemental Reading

- [A People's Guide to AI, 2nd Edition](https://store.alliedmedia.org/collections/a-peoples-guide-to-tech/products/digital-download-a-peoples-guide-to-ai-2nd-edition) from Allied Media.
- [ImageNet: The Data That Transformed AI Research—and Possibly the World](https://qz.com/1034972/the-data-that-changed-the-direction-of-ai-research-and-possibly-the-world/) by Dave Gershgorn.
- [How we teach computers to understand pictures](https://www.youtube.com/watch?v=40riCqvRoMs) by Fei-Fei Li
- [Excavating AI: The Politics of Images in Machine Learning Training Sets](https://www.excavating.ai) by Kate Crawford and Trevor Paglen.

### Related Projects

- [Getting Alexa to Respond to Sign Language Using Your Webcam and TensorFlow.js](https://medium.com/tensorflow/getting-alexa-to-respond-to-sign-language-using-your-webcam-and-tensorflow-js-735ccc1e6d3f) by Abhishek Singh. [ [Live Demo](https://shekit.github.io/alexa-sign-language-translator/) ]
- [Project Euphonia](https://www.youtube.com/watch?v=OAdegPmkK-o) from Google.
- [Objectifier Spatial Programming](https://experiments.withgoogle.com/ai/objectifier-spatial-programming) by Bjørn Karmann.
- [Emoji Scavenger Hunt](https://emojiscavengerhunt.withgoogle.com/).
- [Webcam Pacman](https://storage.googleapis.com/tfjs-examples/webcam-transfer-learning/dist/index.html) by Google’s TensorFlow.js Team.
- [Pong ML](https://github.com/matamalaortiz/Pong-ML) by Alejandro Matamala Ortiz.
- [Teachable Snake](https://experiments.withgoogle.com/teachable-snake) by Vince MingPu Shao.
- [Teachable Arcade](https://ryancan.build/projects/teachable-arcade) by Ryan Flomerfelt Mather.
- [Tiny Sorter](https://experiments.withgoogle.com/tiny-sorter) by Google Creative Lab.
- [Eyeo Festival 2019 - Coding Train](https://vimeo.com/354276216) with Daniel Shiffman. [ [GitHub Repo](https://github.com/CodingTrain/Eyeo-Festival-2019) ]
- [Asemic Writing Teachable Machine](http://blog.jzhong.today/computationaltypo/Asemic-Writing-Teachable-Machine/) by Jillian Zhong.

## Assignment

1. Explore [ImageNet](http://image-net.org/index), [ImageNet sample images](https://github.com/EliSchwartz/imagenet-sample-images/blob/master/gallery.md), [Kaggle ImageNet Mini 1000](https://www.kaggle.com/datasets/ifigotin/imagenetmini-1000). What surprises you about this data set? What questions do you have?
2. Using the [code examples above](#code-examples), try running image classification on a variety of images. What does the model recognize properly? What does it not recognize? What other aspects of the image affect the classification, including but not limited to position, scale, lighting, etc. You are welcome to use the provided examples as they are or modify the code to create interactive experience that reflects your creativity and curiosity! Read and reflect on [Excavating AI: The Politics of Images in Machine Learning Training Sets](https://www.excavating.ai) by Kate Crawford and Trevor Paglen.
3. Train your own image classifier using Teachable Machine and apply the model to an interactive p5.js sketch. Feel free to try sound instead of or in addition to images.
4. Document your thoughts and coding exercises in a post and add a link on the [Assignment 1 Wiki page](https://github.com/shiffman/ML-for-Creative-Coding/wiki).
