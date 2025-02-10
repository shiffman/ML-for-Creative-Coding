# Image Segmentation Models

- [Image Segmentation Slides](https://docs.google.com/presentation/d/17HjMxSuYw2DV3VI_i2zbg9ytQqoKJ7EuPjRZCoERWOI/edit?usp=sharing)

## p5.js and pixels

- 🚂 [2016 Pixel Array Video Tutorial](https://youtu.be/nMUMZ5YRxHI)
- 🎥 [Image Pixelation in p5.js](https://youtu.be/ounnzeu0NQw) by Jack B. Du
- 📋 [p5.js pixel array documentation](https://p5js.org/reference/p5/pixels/)
- 📋 [p5.js mask()](https://p5js.org/reference/p5.Image/mask/)
- 📋 [p5.js createImage()](https://p5js.org/reference/p5/createImage/)

## Async and Await

The TensorFlow.js and Transformers.js examples below make extensive use of the `async` and `await` keywords. These are JavaScript features that simplify handling asynchronous operations, such as loading machine learning models or processing image data.

While `async` and `await` are not currently part of p5.js, they can still be used in a p5.js sketch. However, p5.js **2.0** will introduce official support for `async` functions.

### Learn More:

- 🎥 [Async & Await Video](https://youtu.be/XO77Fib9tSI?list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx) – A standalone video from a larger playlist on Promises. To understand the full context, go back two videos in the playlist.
- 📖 [MDN Docs: Async Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- 📖 [MDN Docs: Await Expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)

## Image Segmentation in JS

### ml5.js

- [ml5.imageSegmenter Reference](https://ml5js.org/reference/imageSegmenter)
- [ml5.bodySegmentation Reference](https://docs.ml5js.org/#/reference/body-segmentation)
- [Introducing BodyPix: Real-time Person Segmentation in the Browser with TensorFlow.js](https://medium.com/tensorflow/introducing-bodypix-real-time-person-segmentation-in-the-browser-with-tensorflow-js-f1948126c2a0)

### TensorFlow.js

- [Image segmentation guide](https://ai.google.dev/edge/mediapipe/solutions/vision/image_segmenter)
- [Deeplab v3 paper: Rethinking Atrous Convolution for Semantic Image Segmentation](https://arxiv.org/pdf/1706.05587v3)
- [Semantic Segmentation in the Browser: DeepLab v3 Model](https://github.com/tensorflow/tfjs-models/tree/master/deeplab)

#### DeepLabv3 Model Variants and Datasets

- [Pascal VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/) - This dataset includes 20 object categories such as person, animal, vehicle, and indoor objects.
- [ADE20K](https://github.com/CSAILVision/ADE20K) - A more diverse dataset with 150 classes, including a wide range of scenes and object categories.
- [Cityscapes](https://www.cityscapes-dataset.com/) - Focused on urban street scenes, this dataset contains 30 classes related to road environments.

### Transformers.js

- [Hugging Face Hub: Image Segmentation Models for Transformers.js](https://huggingface.co/models?pipeline_tag=image-segmentation&library=transformers.js&sort=trending)
- [Segment Anything Demo](https://huggingface.co/spaces/webml-community/segment-anything-webgpu)
- [Background Removal Demo](https://huggingface.co/spaces/Xenova/remove-background-webgpu)
- [Depth Anything Demo](https://huggingface.co/spaces/Xenova/webgpu-depth-anything)

## 💻 Code Examples

### ml5.js

- [BodySegmentation Mask Background](https://editor.p5js.org/ml5/sketches/KNsdeNhrp)
- [BodySegmentation Mask Person](https://editor.p5js.org/ml5/sketches/h6TN8umP5)
- [BodySegmentation Mask Body Parts](https://editor.p5js.org/ml5/sketches/ruoyal-RC)
- [BodySegmentation Select Body Parts](https://editor.p5js.org/ml5/sketches/R5rug0HKk)

### TensorFlow.js

- [DeepLabv3 Image Segmentation with Image](https://editor.p5js.org/ml_4_cc/sketches/9lNNLp0UY)
- [DeepLabv3 Image Segmentation with Live Video](https://editor.p5js.org/ml_4_cc/sketches/sb3fNHVzc)
- [DeepLabv3 Image Segmentation with Recorded Video](https://editor.p5js.org/ml_4_cc/sketches/xILkf9Eo3)

### Transformers.js

- [Image Segmentation Pipeline](https://editor.p5js.org/ml_4_cc/sketches/xEvvqdOQX)
- [Also, depth estimation!](https://editor.p5js.org/ml_4_cc/sketches/WwjFdBMO3) - it's kind of like image segmentation?

## Other Reference and Inspiration

- 📃 [Computer Vision for Artists and Designers](https://www.flong.com/archive/texts/essays/essay_cvad/index.html) by Golan Levin
- 🎨 [Shadow Monsters](https://www.moma.org/collection/works/110196) by Philip Worthington, [Video from Installation](https://youtu.be/XNHv6VryB8o)
- 🎨 [Text Rain](https://camilleutterback.com/projects/text-rain/) by Camille Utterback and Romy Achituv
- 📋 [Beginner’s Guide to Image Segmentation](https://www.v7labs.com/blog/image-segmentation-guide) by V7 Labs
- 📋 [Segment Anything Model (SAM)](https://segment-anything.com/) by Meta AI

## 📚 Assignment

- Read [Computer Vision for Artists and Designers](https://www.flong.com/archive/texts/essays/essay_cvad/index.html).
- Experiment with the provided code examples using ml5.js, TensorFlow.js, or Transformers.js. Try applying the models to different images and videos. Can you think of a creative way to integrate image segmentation into an interactive project?
- Document your experiments and share it on the [Assignment 3 Wiki](https://github.com/shiffman/ML-for-Creative-Coding/wiki/Assignment-3).
