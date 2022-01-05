# Gender-and-Age-Detection
* guess the gender and age of the person (face) in a picture 
* the models trained by [Tal Hassner and Gil Levi](https://talhassner.github.io/home/projects/Adience/Adience-data.html). 
* The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). 
* The CNN Architecture <br/>
The convolutional neural network for this python project has 3 convolutional layers:<br/>

Convolutional layer; 96 nodes, kernel size 7<br/>
Convolutional layer; 256 nodes, kernel size 5<br/>
Convolutional layer; 384 nodes, kernel size 3<br/>
It has 2 fully connected layers, each with 512 nodes, and a final output layer of softmax type.

* [The Dataset](https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification)

