# TensorFlow.js

## Pre-Trained Models

- [TensorFlow.js Models](https://github.com/tensorflow/tfjs-models)

### Object Detection

**Resources**

- [TensorFlow Object Detection API](https://github.com/tensorflow/models/blob/master/research/object_detection/README.md)
- [TensorFlow.js coco-ssd documentation](https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/README.md)

**Examples**

- [COCO-SSD image with p5.js](https://editor.p5js.org/ml_4_cc/sketches/mnLF9Iu4V)
- [COCO-SSD video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/-Yt7vSA5U)

### Image Segmentation

**Resources**

- [Semantic Segmentation in the Browser: DeepLab v3 Model](https://github.com/tensorflow/tfjs-models/blob/master/deeplab/README.md)

**Examples**

- [DeepLabv3 Segmentation image with p5.js](https://editor.p5js.org/ml_4_cc/sketches/9lNNLp0UY)
- [DeepLabv3 Segmentation live video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/sb3fNHVzc)
- [DeepLabv3 Segmentation recorded video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/xILkf9Eo3)

## Training a Neural Network in TensorFlow.js

- [Training a Model Guide](https://www.tensorflow.org/js/guide/train_models#:~:text=In%20TensorFlow,train%20a%20machine%20learning%20model)
- [All Coding Train TensorFlow.js Video Tutorials](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YIeVA3dNxbR9PYj4wV31oQ)

### Core Concepts

- [tf.sequential](https://js.tensorflow.org/api/latest/#sequential): A simple neural network model where layers are stacked in order.
- [tf.layers](https://js.tensorflow.org/api/latest/#Layers): Individual building blocks of a neural network, such as dense layers or convolutional layers.
  - **Dense Layer**: A fully connected neural network layer where each neuron connects to all neurons in the previous layer.
- [tf.tensor](https://js.tensorflow.org/api/latest/#tensor): Data structure for multi-dimensional arrays.
- **Optimizer**: An algorithm that updates the model’s weights to minimize the loss function, e.g. `'adam'`.
- **Loss Function**: Measures how far the model's predictions are from the actual values.
- **Activation Function**: Function applied to neuron outputs.
  - **Softmax Function**: Converts model outputs into probabilities for classification tasks.
  - **ReLU (Rectified Linear Unit)**: Activation function allowing positive values to pass unchanged while setting negative values to zero.
  - **Sigmoid Function**: Activation function used specifically in the autoencoder example to output pixel values scaled between 0 and 1.
- **Epoch**: One full pass through the entire training dataset during training.
- **Batch Size**: The number of training examples used in a single training step.
- **One-Hot Encoding**: Representing categorical labels as binary vectors.
- **Tensor Memory Management**: Manual handling of memory allocation and disposal for tensors using methods like `tf.dispose()` and `tf.tidy()`.

### Code Examples

- [Hand Pose Classifier with TensorFlow.js](https://github.com/shiffman/ml5-neural-network-example/tree/main/tfjs)

## Other Demonstrations

### Feature Extraction

**Resources**

- [Transfer learning image classifier](https://www.tensorflow.org/js/tutorials/transfer/image_classification#:~:text=In%20this%20tutorial%2C%20you%20will,js)
- [How to make your own Teachable Machine in TensorFlow.js](https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine)
- [Cosine Similarity Video Tutorial](https://youtu.be/e9U0QAFbfLI)
- [Google Arts & Culture | X Degrees of Separation](https://artsexperiments.withgoogle.com/xdegrees/)

**Examples**

- [Simple p5.js Teachable Machine](https://github.com/shiffman/ml5-neural-network-example/tree/main/tfjs/teachable-machine)
- [Image Similarity with MobileNet and TensorFlow.js](https://github.com/shiffman/ml-for-creative-coding-examples/tree/main/tfjs/image-similarity)

### Autoencoders

**Resources**

- [2 Minute Papers Autoencoder Video](https://youtu.be/Rdpbnd0pCiI)
- [Building an Autoencoder in Keras](https://blog.keras.io/building-autoencoders-in-keras.html)
- [Coding Train Autoencoder Repo](https://github.com/CodingTrain/Auto-Encoder-Demo) ([part 1](https://www.youtube.com/watch?v=Y9w2PYfIf34), [part 2](https://www.youtube.com/watch?v=SA7W7rlyc3c), [part 3](https://www.youtube.com/watch?v=Ppif4qdW2pE))

**Examples**

- [TensorFlow.js Autoencoder Example](https://github.com/shiffman/ml-for-creative-coding-examples/tree/main/tfjs/autoencoder)

## Creative Projects and Inspiration

- [Google Arts & Culture | X Degrees of Separation](https://artsexperiments.withgoogle.com/xdegrees/)
- [Veremin: Digital Theremin](https://vabarbosa.com/veremin/)
- [Generating Abstract Patterns with TensorFlow](https://blog.otoro.net/2016/03/25/generating-abstract-patterns-with-tensorflow/)
- [Time Series Forecasting with TensorFlow.js](https://jinglescode.github.io/time-series-forecasting-tensorflowjs/)

## Assignment

- Complete the [ML Sketch project](https://github.com/shiffman/ML-for-Creative-Coding/blob/main/projects/ml-sketch/README.md), due March 7th.
