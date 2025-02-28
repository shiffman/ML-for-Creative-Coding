# TensorFlow.js

## Pre-Trained Models

- [TensorFlow.js Models](https://github.com/tensorflow/tfjs-models)

### Object Detection

- [TensorFlow Object Detection API](https://github.com/tensorflow/models/blob/master/research/object_detection/README.md)
- [TensorFlow.js coco-ssd documentation](https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/README.md)
- [COCO-SSD image with p5.js](https://editor.p5js.org/ml_4_cc/sketches/mnLF9Iu4V)
- [COCO-SSD video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/-Yt7vSA5U)

### Image Segmentation

- [Semantic Segmentation in the Browser: DeepLab v3 Model](https://github.com/tensorflow/tfjs-models/blob/master/deeplab/README.md)
- [DeepLabv3 Segmentation image with p5.js](https://editor.p5js.org/ml_4_cc/sketches/9lNNLp0UY)
- [DeepLabv3 Segmentation live video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/sb3fNHVzc)
- [DeepLabv3 Segmentation recorded video with p5.js](https://editor.p5js.org/ml_4_cc/sketches/xILkf9Eo3)

## Training a Neural Network in TensorFlow.js

- [Training a Model Guide](https://www.tensorflow.org/js/guide/train_models#:~:text=In%20TensorFlow,train%20a%20machine%20learning%20model)

### Core Concepts

- [tf.sequential](https://js.tensorflow.org/api/latest/?_gl=1*wrlqe5*_ga*NzEzMzc2NzY2LjE3MzMzNTU0ODM.*_ga_W0YLR4190T*MTc0MDYxOTM1OC41LjEuMTc0MDYxOTQwMS4wLjAuMA..#sequential): A simple neural network model where layers are stacked in order.
- [tf.layers](https://js.tensorflow.org/api/latest/?_gl=1*wrlqe5*_ga*NzEzMzc2NzY2LjE3MzMzNTU0ODM.*_ga_W0YLR4190T*MTc0MDYxOTM1OC41LjEuMTc0MDYxOTQwMS4wLjAuMA..#Layers): Individual building blocks of a neural network, such as dense layers or convolutional layers.
  - **Dense Layer**: A fully connected neural network layer where each neuron connects to all neurons in the previous layer.
- [tf.tensor](https://js.tensorflow.org/api/latest/?_gl=1*wrlqe5*_ga*NzEzMzc2NzY2LjE3MzMzNTU0ODM.*_ga_W0YLR4190T*MTc0MDYxOTM1OC41LjEuMTc0MDYxOTQwMS4wLjAuMA..#tensor) - Data structure for multi-dimensional array
- **Optimizer**: An algorithm that updates the model’s weights to minimize the loss function, e.g. `'adam'`.
- **Loss Function**: Measures how far the model's predictions are from the actual values.
- **Activation Function**: Function for the neuron outputs!
  - **Softmax Function**: Converts model outputs into probabilities for classification tasks.
  - **ReLU (Rectified Linear Unit)**: Activation function that allows positive values to pass unchanged while setting negative values to zero.
- **Epoch**: One full pass through the entire training dataset during training.
- **Batch Size**: The number of training examples used in a single training step.
- **One-Hot Encoding**: Representing categorical labels as binary vectors.

### Code

- [Hand Pose Classifier with TensorFlow.js](https://github.com/shiffman/ml5-neural-network-example/tree/main/tfjs)

## Feature Extraction

- [Transfer learning image classifier](https://www.tensorflow.org/js/tutorials/transfer/image_classification#:~:text=In%20this%20tutorial%2C%20you%20will,js)
- [Simple p5.js Teachable Machine](https://github.com/shiffman/ml5-neural-network-example/tree/main/tfjs/teachable-machine)

### Related Projects

- [Google Arts & Culture | X Degrees of Separation](https://artsexperiments.withgoogle.com/xdegrees/)
