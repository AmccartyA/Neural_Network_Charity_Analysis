# Neural_Network_Charity_Analysis

## Overview
Using machine learning and neural networks, I put together a binary classifier that will hopefully predict future applicants who will be successful if funded by Alphabet Soup.

Using a data sheet containing more than 34,000 organizations currently funded by alaphabet soup. I ran the data through a neural network model to see if there was a way to accurately predict success with higher than 75% accuracy.
## Results
### Data Preprocessing
* After reviewing the Data, we targeted the Is_Successful Column to base our model on potential clients

* We included all binary columns from the data as features. 

* We then removed EIN and Name columns as they are not targerts or features

### Compiling, Training, and Evaluating the model

* For my first attempt I Used 3 hidden layers. The first layer had 100 neurons and the second had 50 and the third had 25. I used "relu", "selu" and "sigmoid" for the activation methos. 
![FirstTry](https://user-images.githubusercontent.com/103524591/197802737-d35f3501-7a31-4dd3-b248-04b46086491d.png)

* I was not able to achieve the 75% accuracy performance

* To increase the models performance i changed the activation methods, raised the basis to which add features. Then I raised the number of epochs processed and added 2 more layers to the neurons level. 
![Test2](https://user-images.githubusercontent.com/103524591/197802710-dbccced0-625a-4ed4-b021-9c122e28bfd6.png)

## Summary 
Using my knowledge of machine learning, I was only able to get a accuracy rating of 53%. In my three attempts to get a higher accuracy, I mainly added more layers to the process and changed the activation between relu, selu and sigmoid. To get that 75% score I would continue to exclude certain freatures going foreward.
