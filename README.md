# Sarcasm-Detection-on-"News-Headlines-Dataset"-
Detection of sarcastic headlines using different Machine Learning techniques, which are:

Logistic Regression\
Percepton \
KNN

**Description:**

First tweets were separated from it classes, which was given in shape of binary label. Later data (tweets) was processed to remove unncessary information from it, like puntuations and stop words.
Then **GoogleNews word2vec**, word vector model was used to get repressentive vector (1x300 dimensional) for each word of the processed tweets. Single tweet is represented by sum of all the 300 dimensional vectors of each word, returned by the model.

Each 300 dimensional vector was used as input to classify the tweets/headlines.

**Results:**

KNN (K-Nearest Neighbors) worked best for the problem, among the algorithms mentioned above.

The results from each model trained for the probelm, are shown below:

**Logistic Regression:**

![alt text](https://github.com/WaizKhan7/Sarcasm-Detection-using-News-Headlines-Dataset-for-Sarcasm-Detection-/blob/master/Results/LR.JPG?raw=true)

**Perceptron:**

![alt text](https://github.com/WaizKhan7/Sarcasm-Detection-using-News-Headlines-Dataset-for-Sarcasm-Detection-/blob/master/Results/perceptron.JPG?raw=true)

**KNN:**

![alt text](https://github.com/WaizKhan7/Sarcasm-Detection-using-News-Headlines-Dataset-for-Sarcasm-Detection-/blob/master/Results/KNN.JPG?raw=true)
