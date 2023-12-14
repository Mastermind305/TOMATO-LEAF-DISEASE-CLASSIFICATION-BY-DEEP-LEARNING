Tomato Leaf Diseases Classification Deep Learning Models

This repository contains deep learning models for classifying tomato leaf diseases using various architectures. The models included in this repository are:

1. ResNet Model
   - File: `tomato_ResNet_50.ipynb`
   - Accuracy: 99.40%

2. VGG-16 Model
   - File: `tomato_leaf_vgg_16.ipynb`
   - Accuracy: 93.99%

3. Sequential Model
   - File: `sequential.ipynb`
   - Accuracy: 93.08%

4. Ensemble of ResNet and VGG-16
   - File: `Ensemble.ipynb`


1. ResNet Model
The ResNet model achieved an impressive accuracy of 99.40%. The ResNet architecture is known for its ability to train very deep networks, overcoming the vanishing gradient problem

2. VGG-16 Model
The VGG-16 model achieved a notable accuracy of 93.99%. VGG-16 is a classic architecture with a focus on simplicity and uniform architecture, using 3x3 convolutional layers.

3. Sequential Model
The Sequential model, designed with a simpler architecture, achieved a commendable accuracy of 93.08%. The Sequential model is a linear stack of layers, making it a straightforward yet effective choice for certain tasks.

4. Ensemble Model
The ensemble model (`Ensemble.ipynb`) combines the strengths of both the ResNet and VGG-16 models to potentially improve overall performance. Ensemble learning involves combining predictions from multiple models to achieve better results by averaging.


Usage
- Each model file (`tomato_ResNet_50.ipynb`, `tomato_leaf_vgg_16.ipynb`, `sequential.ipynb`) can be used independently for training or inference.
- The ensemble model can be used for predictions by loading both the ResNet and VGG-16 models and combining their outputs.

Dependencies
- The code is written in Python and requires deep learning libraries such as TensorFlow.
- Make sure to install the necessary dependencies

Feel free to explore and adapt these models for your own tomato leaf disease classification tasks. If you have any questions or suggestions, please don't hesitate to reach out. Happy coding!
