# Deep-Learning-Kaggle-Competition---Invasive-Species-Detection

This is a deep Learning Kaggle competition. The objective is to build a model that can detect invasive Hydrangea in images of the Brazilian National Forest.

To complete the project I built a relatively simple but effective Convolutional Neural Network, which yielded surprisingly good accuracy. I then harnessed the power of the VGG16 pretrained model offered by Keras, which took an absurd amount of time to train on my CPU, but yielded excellent results.

My third attempt was to use transfer learning to harness the weights of the ResNet50 model and feed them into another simple CNN. This model yielded significantly worse results.

My best model landed me in the top 25% of the public leaderboard on Kaggle, and gave an ROC score of nearly .99.
