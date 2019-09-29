

# Assignment 02

```
Build a binary classifier for human versus horse based on logistic regression using the dataset that consists of human and horse images
```


## Dataset

- The dataset consists of human images and horse images for the training and the validation
- The classifier should be trained using the training set
- The classifier should be tested using the validation set
- Vectorize an input image matrix into a column vector

## Implementation

- Write codes in python programming
- Use ```jupyter notebook``` for the programming environment
- You can use any libarary
- You have to write your own implementation for the followings:
    - compute the loss
    - compute the accuracy
    - compute the gradient of the model parameters with respect to the loss
    - update the model parameters
    - plot the results

## Optimization

- Apply the gradient descent algorithm with an appropriate learning rate
- Apply the number of iterations that lead to the convergence of the algorith
- Use the vectorization scheme in the computation of gradients and the update of the model parameters

## git commit

- Apply a number of ```git commit``` at intermediate development steps with their descriptive comments 

## Output

- Plot the elapsed time at every iteration for the computation of the gradient and the update of model parameters (x-axis: iteration, y-axis: elapsed time)
- Plot the training loss at every iteration (x-axis: iteration, y-axis: loss)
- Plot the validation loss at every iteration (x-axis: iteration, y-axis: loss)
- Plot the training accuracy at every iteration (x-axis: iteration, y-axis: accuracy)
- Plot the validation accuracy at every iteration (x-axis: iteration, y-axis: accuracy)
- Present the table for the final accuracy and loss with training and validation datasets as below:

| dataset    | loss       | accuracy   | 
|:----------:|:----------:|:----------:|
| training   |            |            |
| validation |            |            |

## Submission

- A PDF file exported from jupyter notebook for codes, results and comments [example: 20191234_02.pdf]
- A PDF file exported from the github website for the history of git commit [example: 20191234_02_git.pdf]
