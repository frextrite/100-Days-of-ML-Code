# 100 Days of Machine Learning - frextrite's Log

A little bit of background: I have been involved in Machine Learning since the past year or so. I've taken university courses and online courses(Andrew NG's, Udacity's Intro to Machine Learning and currently taking up Andrew NG's course on CNN) in this brief period of time. However, I've been into ML on and off(well, mostly off), and just have basic knowledge of scikit-learn and tensorflow. With this 100 Days of ML Code challenge I would like to strengthen my code writing skills that is get an insight into sci-kit learn library, tensorflow and also keras.

## Day 0: July 6, 2018
 
**Today's Progress** : Initialised the repository to keep track of my 100 Days of ML journey

**Thoughts** : Hope I can continue through the 100 days and do not stop in between :)

## Day 1: July 7, 2018
 
**Today's Progress** : Created a simple Linear Regression model using scikit-learn library, baby-steps! Also, scraped Kaggle for ML datasets.

**Thoughts** : Maybe implement my own version of Linear Regression model in the future

**Link to work** : [Linear Regression Model](https://github.com/frextrite/100-Days-of-ML-Code/tree/master/Day%201)

## Day 2: July 8, 2018
 
**Today's Progress** : Created a single layered Neural Network MNIST classifier using tensorflow. That's a combined dive into the world of tensorflow and neural networks!

**Thoughts** : The official tensorflow tutorial, MNIST for ML Beginners is really good as everything is explained in deep. I'm thinking of implementing a Deep Neural Network MNIST classifier and a CNN MNIST classifier and compare their accuracy.

**Link to work** : [MNIST Classifier](https://github.com/frextrite/100-Days-of-ML-Code/tree/master/Day%202)

## Day 3: July 9, 2018
 
**Today's Progress** : Created a Deep Neural Network MNIST Classifier. Learned a few things about tensorflow and Neural Networks in general while constructing this model, details inside the work folder.

**Thoughts** : Increasing the depth of a Neural Network and increasing the number of epochs increases the accuracy of the model but this tends to saturate at a particular limit. Further increase in both doesn't result in greater accuracies.

**Link to work** : [MNIST Classifier Deep](https://github.com/frextrite/100-Days-of-ML-Code/tree/master/Day%203)

## Day 4: July 10, 2018
 
**Today's Progress** : Studied about various optimization techniques, including Gradient Descent and Adam Optimizer.

**Thoughts** : Implement my own various of these optimizing techniques maybe.

## Day 5: July 11, 2018
 
**Today's Progress** : Attempted first assignment of Week 1 of Coursera's Convolutional Neural Networks course where I implemented forward propagation from scratch using numpy.

**Thoughts** : CNNs are fun! numpy is a powerful library!

**Course Link** : [Convolutional Neural Networks](https://www.coursera.org/learn/convolutional-neural-networks/)

## Day 6: July 12, 2018
 
**Today's Progress** : Fixed my Deep MNIST Classifier and implemented SGD correctly. Getting higher accuracy with the new model. Also watched an introduction video for tensorflow js.

**Thoughts** : I think I've hit the accuracy ceiling with Deep Neaural Networks, time for CNN model.

**Link to work** : [MNIST Classifier Deep](https://github.com/frextrite/100-Days-of-ML-Code/tree/master/Day%203)

## Day 7: July 13, 2018
 
**Today's Progress** : Created Convolution Neural Network model for MNIST classifier. Learned a lot about CNNs in this process.

**Thoughts** : I will retrain the model with more epochs and hope for higher accuracy. Dropouts really help a lot.

**Update** : Reran the model with updated dropout probabilities and got an increase in accuracy.

**Link to work** : [MNIST CNN Classifier](https://github.com/frextrite/100-Days-of-ML-Code/tree/master/Day%207)

## Day 8: July 14, 2018
 
**Today's Progress** : Thought of creating a CNN classifier for classifying cats and dogs. PC ran out of memory loading the images.

**Thoughts** : Find an optimized way of loading images or get more RAM.

## Day 9: July 15, 2018
 
**Today's Progress** : Watched videos on how to load images into python and convert them into arrays. Also dived into tf.keras

**Thoughts** : Use tf.keras for quicker model initialization.

## Day 10: July 16, 2018
 
**Today's Progress** : Going a bit theoretical for a few days.

## Day 11: August 4, 2018
 
**Today's Progress** : Read few articles and watched videos on RNN. Grasped the basic idea behind RNNs but still need to figure out its inner workings.

**Thoughts** : Time to read papers/more articles related to RNN and its implementation.

## Day 12: August 5, 2018
 
**Today's Progress** : Reading MSCOCO Dataset Paper. Read few more articles on RNN and NLP. Preping for a huge project coming up ahead.

## Day 13: August 6, 2018
 
**Today's Progress** : Read Show and Tell: A Neural Image Caption Generator paper. Finally cleaned up the code and uploaded my Dogs vs Cats CNN Classifier on GitHub, which I implemented during my off days.

**Thoughts** : I will implement a Neural Image Caption Generator next. Before that I'll get my hands dirty on nltk and basic LSTM cell.

**Link to work** : [Cats Dogs CNN Classifier](https://github.com/frextrite/CatsDogsClassifier)

## Day 14: August 7, 2018
 
**Today's Progress** : Getting my hands dirty on nltk. Started work on a simple positive and negative sentence classifier.

**Thoughts** : To complete an advanced project you first gotta build your basics.

## Day 15: August 8, 2018
 
**Today's Progress** : Continuing building the pos neg classifier.

**Thoughts** : Pre-processing data is challenging!

## Day 16: August 9, 2018
 
**Today's Progress** : Finally completed my pos neg classifier. Also this is my first keras implementation.

**Thoughts** : Get more data when working on a Deep Neural Network!

## Day 17: August 10, 2018
 
**Today's Progress** : Watching Andrej Karpathy's lecture on Recurrent Neural Networks, Image Captioning and LSTM(Winter 2016). Learnt about vanishing and exploding gradient problem.

**Link to work** : [CS231n Winter 2016: Lecture 10: Recurrent Neural Networks, Image Captioning, LSTM - Andrej Karpathy](https://youtu.be/yCC09vCHzF8)

## Day 18: August 11, 2018
 
**Today's Progress** : Initialised Neural Image Caption repository on Github.

**Link to work** : [Neural Image Caption](https://github.com/frextrite/Neural-Image-Caption)

## Day 19: August 12, 2018
 
**Today's Progress** : Pre processing Image and Caption data for Neural Image Caption.

**Link to work** : [Neural Image Caption](https://github.com/frextrite/Neural-Image-Caption)

## Day 20: August 13, 2018
 
**Today's Progress** : Finished implementing Neural Image Caption using keras. Basic training done on Flickr8k dataset and decent results were obtained.

**Thoughts** : Read more about LSTMs and RNNs. Find the best model which gives optimal results. Train on Flickr30k and if possible on MSCOCO dataset as well. Add comments and improve readability of the code.

**Link to work** : [Neural Image Caption](https://github.com/frextrite/Neural-Image-Caption)

## Day 21: August 14, 2018
 
**Today's Progress** : Experimenting with different encoder decoder models(CNN RNN) that would give optimal results. Trained basic model on Flickr30k for 10 hours, results unsatisfactory.

## Day 22: August 15, 2018
 
**Today's Progress** : Training-tweaking models, hoping for better results, result negative.

## Day 23: August 16, 2018
 
**Today's Progress** : Re-trained my NIC model on Flickr30k dataset for 2 epochs(2 hours/epoch) and the model learnt to spell out a bunch of 'a's. Disaster!

**Thoughts** : Train for more epochs.
