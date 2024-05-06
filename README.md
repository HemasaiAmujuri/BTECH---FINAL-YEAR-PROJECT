# BTECH---FINAL-YEAR-PROJECT
 1.Our B-Tech Final Year Project is Traffic Sign Recognition. I collecting our traffic sign dataset in kaggle,I didnt get sufficient data of Indian dataset so we move to German Traffic Sign data which is sufficient 
   for me.
 2.When i download dataset from kaggle it takes more local storage.
 3.I start this project in Colab so i install kaggle in colab,by using kaggle api key, i download dataset into Colab storage.
 4.As a first step of my project i import all the required dependencies like numpy,pandas,matplotlib,tensorflow,keras,convolutional neural network,
 5.Now i did a preprocessing step i.e,the images of train dataset has not in unique size it leads to problem in training.So i convert all the training images into unique size(30*30).
 6.After the preprocessing step, we split our dataset into train and test in the ratio of 8:2.
 7.Now,import the sequential model of CNN.In this model building we have used different CNN layers i.e ,Convolutional layer,Maxpooling layer,Flatten layer,Dense layer and dropout layer.
 8.The Convolutional layer helps to extract features by applying filers.In our model we apply 32 and 64 filters with (5,5) kernal size. 
 9.The Maxpooling layer helps to extract intensified features.
 10.The Flatten layer helps to dimensionality reduction.It helps to multidimensional to one dimensional.
 11.The purpose of Dense layer is every neuron in one layer to every neuron in another layer it helps to predict.
 12.The Dropout layer helps to prevent from overfitting .In our model, we use rate 0.25 in dropout layer.
 13.In this model we use RELU and SOFTMAX activation function.Activation function helps to find Non-Linearity of the model ,the relu function has less computational efficiency because of simple formula and the 
   softmax function used in output layer for classification.
 14.In our model we have 20 epochs with batch_size 32.
 15.After the model building its time to find accuracy,the accuracy of my model is 98 percent.
 16.Finally, we save our model by using pickle library.
 
 
             
