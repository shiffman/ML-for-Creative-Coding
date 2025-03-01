# Training a Neural Network

- [Neural Network Slides](https://docs.google.com/presentation/d/1NqBjHPStaYl2vlZKPisLp4XsyHatoUFvFk-HpQig6ns/edit?usp=sharing)

## ml5.neuralNetwork()

- [ml5.neuralNetwork() Reference](https://docs.ml5js.org/#/reference/neural-network)
- [NeuralNetwork - Color Classifier](https://editor.p5js.org/ml5/sketches/eGHBdmCLe)
- [NeuralNetwork - Mouse Gesture](https://editor.p5js.org/ml5/sketches/FdXAgrA3N)
- [NeuralNetwork - Train and Save](https://editor.p5js.org/ml5/sketches/rR51vvi-u)
- [NeuralNetwork - Load Model](https://editor.p5js.org/ml5/sketches/U-aljtx7x)

## Code Examples
- [ml5.js Pose Classifier: data collection, model training, model deployment (GitHub)](https://github.com/shiffman/ml5-neural-network-example/tree/main/ml5js/pose-classifier)
   - [Data Collection - classifier (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/mhNTFKLpz)
   - [Train Model - classifier  (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/TN9d52IcI)
   - [Deploy Model - classifier  (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/NPIxC0u--D)
- [ml5.js Pose Regression Model: data collection, model training, model deployment (GitHub)](https://github.com/shiffman/ml5-neural-network-example/tree/main/ml5js/pose-regression)
   - [Data Collection - regression (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/vRMRtbVWR)
   - [Train Model - regression (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/g8wddLHmj)
   - [Deploy Model - regression (p5.js web editor)](https://editor.p5js.org/ml_4_cc/sketches/_BMeZFMcc)


## Supplemental Materials

- [Chapter 10: Neural Network, Nature of Code](https://natureofcode.com/book/chapter-10-neural-networks/) by Daniel Shiffman.
- [But what _is_ a Neural Network?](https://youtu.be/aircAruvnKk?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by 3Blue1Brown.
- [The 7 steps of machine learning](https://www.youtube.com/watch?v=nKW8Ndu7Mjw) from Google Cloud Tech.
- [A Brief History of Neural Nets and Deep Learning](https://www.skynettoday.com/overviews/neural-net-history) by Andrey Kurenkov
- [Neural Network History Wiki](https://github.com/shiffman/ML-for-Creative-Coding/wiki/Neural-Network-History)

## Video Tutorials

### Neural Network Concepts

These videos are about the core concepts behind neural networks and do not use ml5.js or other ML libraries.

- [Neural Networks: Perceptron (2 parts)](https://thecodingtrain.com/tracks/neural-networks/neural-networks/2-perceptron-part-1)
- [Neural Networks: Multilayer Perceptron (2 parts)](https://thecodingtrain.com/tracks/neural-networks/neural-networks/4-multilayer-perceptron-part-1).
- [Neural Networks: Matrix Math](https://thecodingtrain.com/tracks/neural-networks/neural-networks/6-matrix-math-basics)

### ml5.js Neural Network

🚨 _These ml5.js tutorials use an older version of ml5.js, while the concepts and ideas are still relevant the syntax has changed. We will be covering how to to train a neural network using pose detection data in class! The [ml5.js FAQ](https://docs.ml5js.org/#/welcome/faq?id=what-happened-to-older-ml5js-releases) includes additional information._ 🚨

- [ml5.js: Train Your Own Neural Network](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/1-train-the-model)
- [ml5.js: Save Neural Network Training Data](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/2-save-data)
- [ml5.js: Save Neural Network Model](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/3-save-model)
- [ml5: Neural Network Regression](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/6-train-your-own-neural-network/4-regression)
- [ml5.js: Pose Classification with PoseNet and ml5.neuralNetwork()](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-posenet/2-pose-classifier)
- [ml5.js: Pose Regression with PoseNet and ml5.neuralNetwork()](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-posenet/3-pose-regression)

## Assignment  

As a class, we are working towards **March 7th**, where everyone will share a project that applies concepts from the first half of the semester (_pre-trained models with ml5.js, TensorFlow.js, transformers.js_). While training your own model is not required for this project, this week's assignment asks you to imagine an application that would.  

1. Watch [Machine Learning for Human Creative Practice](https://vimeo.com/287094397) by Dr. Rebecca Fiebrink (Eyeo 2018). Reflect on the question: _How can machine learning support and expand creative practices?_  

2. Read [A Brief History of Neural Nets and Deep Learning](https://www.skynettoday.com/overviews/neural-net-history) by Andrey Kurenkov.  

3. Write a short blog post describing a creative application that requires training a custom model. Address the following:  

   - **What is the input?**  
     What data will your model take in? Consider sources such as sensors, body/face/hand keypoints, images, sound, or text. 
     
   - **What is the output?**  
     What will your model predict or generate? Are you classifying labels, predicting continuous values, or something else?  

   - **What kind of learning task is it?**  
     Is this a _classification_ or _regression_ problem? It's okay if you're unsure!  

   - **What challenges do you anticipate?**  
     These could be technical, ethical, or creative obstacles related to data collection, bias, implementation, or user interaction.

4. If you're feeling inspired, start prototyping your idea! You could create a p5.js sketch that collects sample data or explore how a user might interact with your system before training the model.

Document your idea and share it on the [Assignment 4 Wiki](https://github.com/shiffman/ML-for-Creative-Coding/wiki/Assignment-4).


