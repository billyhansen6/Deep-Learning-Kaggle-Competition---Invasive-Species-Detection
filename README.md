## Deep Learning Kaggle Competition - Invasive Species Detection

This is a deep Learning Kaggle competition. The objective is to build a model that can detect invasive Hydrangea in images of the Brazilian National Forest.

To complete the project I performed image augmentation, built a relatively simple but effective Convolutional Neural Network, which yielded surprisingly good accuracy. I then harnessed the power of the VGG16 pretrained model offered by Keras, which took an absurd amount of time to train on my CPU, but yielded excellent results.

My third attempt was to use transfer learning to harness the weights of the ResNet50 model and feed them into another simple CNN. This model yielded significantly worse results.

My best model landed me in the top 25% of the public leaderboard on Kaggle, and gave an ROC score of nearly .99.


<img width="275" alt="aug" src="https://user-images.githubusercontent.com/19575713/41811882-c76170de-76cc-11e8-831d-387b9fa23ee4.png">



<img width="415" alt="results" src="https://user-images.githubusercontent.com/19575713/41811898-fc54d4f2-76cc-11e8-9f26-e1d9bf5be658.png">
