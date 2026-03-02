# smart-sorting-transfer-learning-for-identifying-rotten-fruit-and-vegetable-
Python scripts
train_hero.py: This Python script contains the code for training a model on a given dataset. Parameters to be specified in the argument parser are the dataset, model, label binarizer and the name of the training Loss and Accuracy plot.
test_hero.py: Python script to evaluate the trained model on a test set of images or a single image. Parameters to be specified in the argument parser are the model, label binarizer, location of test image or path to test dataset.
convert_hero.py: Python script for converting the trained model into a core ML model using coremltools. Parameters to be specified in the argument parser are the model and the label binarizer.
transfer_hero.py: Python script based on the train_hero.py script with a transfer learning approach. ResNet50 is used as a base model.

All scripts are optimized to be run in the command line

Sources
The following contains the sources we utilized within this project

Tutorials
https://www.pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/
https://www.pyimagesearch.com/2018/04/16/keras-and-convolutional-neural-networks-cnns/
https://www.pyimagesearch.com/2018/04/23/running-keras-models-on-ios-with-coreml/

Data
https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification
https://www.kaggle.com/moltean/fruits

Information
https://ec.europa.eu/jrc/en/news/eu-households-waste-over-17-billion-kg-fresh-fruit-and-vegetables-year
https://www.theguardian.com/environment/2016/jul/13/us-food-waste-ugly-fruit-vegetables-perfect
https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
https://medium.com/@sidereal/cnns-architectures-lenet-alexnet-vgg-googlenet-resnet-and-more-666091488df5
https://machinelearningmastery.com/transfer-learning-for-deep-learning/
https://keras.io/

