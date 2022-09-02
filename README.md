# Classifying fruits
While I was delving into various classification problems, I came across this interesting read: https://medium.com/@ocktavia/fruits-lovers-solving-a-simple-classification-problem-with-python-e63ae067422c

Essentially the problem statement was this:
> Can we train a classifier to distinguish between Apples, Lemons, Oranges and Mandarin oranges?

## Preparing the Data

A brief description of the data:

<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/data.PNG" width="300" height="100">
<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/Table.PNG" width="250" height="130">

The dataset has 7 features, of which I believe the mass, width, height and colour_score will be important in identifying the fruit_name. 

<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/distributions.png" width="300" height="300">

The mass, height and colour_score seem to be fairly gaussian. Mass and width as well as mass and height seems to have a positive linear relationship.
So this relationship might be modellable, and perhaps distinct for each fruit. 

To run the classification models, the dataset was split into training and testing sets using scikitlearn.model_selection.train_test_split
In addition, the variables were also scaled using scikitlearn.preprocessing.MinMaxScaler

## Models
### 1) Logistic Regression

### 2) Decision Tree classifier

### 3) K-Nearest Neighbours

### 4) Linear Discriminant Analysis

### 5) Gaussian Naive Bayes

### 6) Support Vector Machine
