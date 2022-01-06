## Module 19 Challenge Alphabet Soup. 

I. Here, preprocessing methodology to performing neural network via sklearn, tensorflow, and pandas.


### Results 
#### Deliverable 1 requirements.
    'EIN' and 'NAME' drop
    DataFrame
   ![Figure 1](https://github.com/davidhyongae2/network/blob/main/Figure1.png) <br>

    The columns with more than 10 unique values have been grouped together 
    
   ![Figure 2](https://github.com/davidhyongae2/network/blob/main/Figure2.png) <br>
    
    The preprocessed data is split into features and target arrays (5 pt)
    The preprocessed data is split into training and testing datasets (5 pt)
    The numerical values have been standardized using the StandardScaler() module (5 pt)
    
   ![Figure 3](https://github.com/davidhyongae2/network/blob/main/Figure3.png) <br>
    
    What variable(s) that are considered the target(s) for your model?

     a. IS_SUCCESSFUL column.

    What variable(s) that are considered to be the features for your model?

     b. Every column except the drop.

    What variable(s) are neither targets nor features, and should be removed from the input data?
  
     c. 'EIN' & 'NAME'???


#### Compiling, Training, and Evaluating the Model

The neural network model using Tensorflow Keras contains working code that performs the following steps:
The number of layers, the number of neurons per layer, and activation function are defined (2.5 pt) <br>

An output layer with an activation function is created (2.5 pt) <br>

There is an output for the structure of the model (5 pt) <br>
There is an output of the model’s loss and accuracy (5 pt) <br>
The model's weights are saved every 5 epochs (2.5 pt) <br>
The results are saved to an HDF5 file (2.5 pt) <br>

   ![Figure 4](https://github.com/davidhyongae2/network/blob/main/Figure4.png) <br>

   ![Figure 5](https://github.com/davidhyongae2/network/blob/main/Figure5.png) <br>

#### Deliverable 3 Requirements

Noisy variables are removed from features (2.5 pt) <br>
Additional neurons are added to hidden layers (2.5 pt) <br>
Additional hidden layers are added (5 pt) <br> 
The activation function of hidden layers or output layers is changed for optimization (5 pt) <br>
The model's weights are saved every 5 epochs (2.5 pt) <br>
The results are saved to an HDF5 file (2.5 pt) <br>

   ![Figure 6](https://github.com/davidhyongae2/network/blob/main/Figure6.png) <br>

How many neurons, layers, and activation functions did you select for your neural network model, and why? <br>
layer1 = 80, layer2 = 30. in other to create a testable and a training set. 
Were you able to achieve the target model performance? <br> 
yes, at an accurancy of 0.7286 <br>
What steps did you take to try and increase model performance? <br>
100 Epoch steps. and period of 5. 

#### Summary: 
the model did well at 73% percentage. 

