# Personal notes, definitions in machine learning

## Types of methods:
1. Supervised Learning
2. Unsupervised Learning
3. Reinforced learning

### Definitions
1. Supervised Learning:
* Uses labels to train data
* Uses the history of the data to predict
* Two types: Classification and Regression
* Example: Hight-Weight of Male and Females

2. Unsupervised learning:
* No historical labels
* You get the data points but you don't have the labels
* Example: Only hight and Weight. no labels at all
* So you have to "cluster data"

3. Reinforcement Learning
Three manin components: Agent (who makes decisions), Environment, and Action. Agent chooses those actions that maximizes the reward over a specific amount of time.

### 1. Supervised Machine Learning:
1. Acquire Data First!
2. Clean and Organize the Data!
3. Split data to train and test sets. 70% for training and 30% for testing.
4. Train the model (fit the model on the training set)
5. Evauate the model on the test set
6. Adjuist the model parameters
7. Deploy new incoming data!

### 1. Unsupervised learning
Well you don't have the labels, so you can't do the spliting and make the train/test sets (you don't know the correct answer).
So you have to use all the data for training and evaluating the model.

### Hold out sets
we split the data to three groups: train, test, holdout
the main purpose of the holdout set is to get some idea of how well your model is gonna perform.
so you tain the model on the train set, test (and adjust) the model parameters with test set, and then evaluate it via holdout set.
*not trying to cheat with test data.*

### Evaulations:
#### Supervised learning: 
1. Classification: Accuracy, correctly classified samples divided by total samples
2. Regression: MAE, MSE, RMSE (how far off are you from the correct value)

#### Unsupervised learning: 
Really tricky problem cuz you don't have the labels to compare to!
you could look at cluster homogeneity, Rand Index

#### Reinforcement Learning
The evaluations in the method is easier cuz we already included an scoring function into the model.

Unsupervised learning: 

