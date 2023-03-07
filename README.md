# ArtificialNeuralNets-and-DeepLearning-Competition1

In this challenge we are required to classify species of plants (like the ones in the example image below), which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label. 

Dataset Details: \
Image size: 96x96 \
Color space: RGB (read as 'rgb' in ImageDataGenerator.flow_from_directory ('color_mode' attribute) or use PIL.Image.open('imgname.jpg').convert('RGB')) \
File Format: JPG \
Number of classes: 8 \
Classes: \
0: "Species1" \
1: "Species2" \
2: "Species3" \
3: "Species4" \
4: "Species5" \
5: "Species6" \
6: "Species7" \
7: "Species8" \


Dataset Structure \
Single folder: \
Ttraining: containing 3542 images already divided in sub-folders, based on their class. \
Training images per class: \
Species1 : 186 \
Species2 : 532 \
Species3 : 515 \
Species4 : 511 \
Species5 : 531 \
Species6 : 222 \
Species7 : 537 \
Species8 : 508 
