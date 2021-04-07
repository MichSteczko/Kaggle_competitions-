# Repo where you can find my solutions to solve Kaggle Competitons problems.
## Table of contents
1. [How to use this repo?](#How-to-use-this-repo)
2. [Full competitions names](#Full-competitions-names)
3. [Projects descriptions](#Projects-descriptions)

### How to use this repo?
  - Every file is named by competition name on Kaggle and if you click on them you can find link to google colab    to see the solution in action.
### Full competitions names
 - NCAAW - March Machine Learning Mania 2021 NCAAW, competition where we have to predict the probability which team will win against other team
 - Mnist - Digit Recognizer, competition where we have to predict which didgit between range (0-9) is in the picture.
### Projects descriptions
1. MNIST (Model with 99.255 accuracy):
  - Data - I used data from this [kaggle competition](https://www.kaggle.com/c/digit-recognizer). Images are represented as       recktangular data where each column contains pixel values between 1 and 255.
  - Model - I used Nadam optimization (Adam optimization with Nesterov trick) and sequential CNN model wchich is represented in the image below. I created self-regularizing neural net (we don't need to use l1 or l2 regularizations) with batch normalization and Alphadropout layers (we can use Monte Carlo Dropout instead) and one-cycle learning rate sheduling.
  - References:
    - [One cycle learning rate sheduling](https://homl.info/1cycle)
       <br/>
       ![mnist_model](https://github.com/MichSteczko/Kaggle_competitions-/blob/main/images/mnist_model.png)
