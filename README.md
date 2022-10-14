# Dogs vs. Cats Computer Vision

The Dogs vs. Cats data set contains images of both animals with 25,000 in the training (labeled) and 12,500 in the test set (unlabeled). The goal of this project is to build a convolutional neural network (CNN) that correctly identifies each image as a dog or cat. The Kaggle competition scores the networks based on the log loss, which considers the probabilities predicted from the models. I configured the networks to be evaluated based on accuracy given its easier interpretability.

The images are varied with different dog and cat breeds, lighting, angles, sizes, positioning of the animals, and backgrounds. Each image is interpreted by the computer as a set of pixels, with each pixel represented by 3 digits ranging from 0 to 255 that correspond to RGB values. EDA shows the training set is evenly divided into dogs and cats (12,500 each).
