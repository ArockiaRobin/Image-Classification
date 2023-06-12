# Image-Classification

Personal skin care assistant using deep learning

A mobile application used to identify skin disease using images captured from camera. 
App is built with Android+AI model with integrates through python pipeline concept. 
images from the android devices are transferred to AI model which classify the skin disease using image classification algorithm on cloud and sends responses to the classified disease names.

The net model was used by applying and transfer learning on the 7 skin diseases to create a skin disease classification system on andriod application.
Proponents gathered a total of 3,406 images and it is considered as a imbalanced dataset because of the unequal number of images in its classes.
Using different sampling method and preprocessing of input data was explored to further improve the accuracy of the MobileNet.
Using an under sampling method and the default preprocessing of input data achieved an 84.28% accuracy.
While using an imbalanced dataset and default preprocessing of input data achieved a 93.6% accuracy.
Then researchers exploded oversampling the dataset and the model attained a 91.8% accuracy. 
Lastly by using oversampling technique and data augmentation on preprocessing the input provide a 94.4% accuracy and this model was developed on the developed android application. 
Idea of the project is to develop a mobile camera application that performs calculations on standalone tensorflow android archive which uses deep learning algorithms to classify the skin diseases through captured images from human skin.

In this applpication we are been using two algorithms: Convolution Neural Network connected to Artifical Neural Network which is pipelined to android application. 

Environment of Technology used: ( CNN Algorithm, Python pipeline, Google cloud and Android MVC )
