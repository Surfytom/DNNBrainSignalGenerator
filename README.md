# Brain Signal Generator

This project was handed in for my deep neural networks assignment for my university module.

It consists of two main files that aim to train and evaluate a model that can generate brain signals from an input image.

The dataset used consists of images and the participants corrisponding brain signal response to those images from specific areas of the brain mainly around the visual cortex. This data can be used to create a model to generate realistic brain signals from input images effectively re-creating the brains visual cortex behaviour. Please consult the [Latex style paper](pdf) that was handed in for the assignment if you are interested.

## Files

### [Assignment.ipynb]()

This file contains the code used to pre-process and train the models used. I used basic convolutional models with a custom cosine loss function to articulate how different the models generated vector was from the original data label. I trained many different models adjusting 5 main hyper-parameters such as layer sizes and regularization. More evaluation of these parameters is shown in the paper.

### [ModelEvaluation.ipynb]()

This file shows the generation code for the graphs used to evaluate the models in the paper. I assessed the models validation/training accuracy and loss.

