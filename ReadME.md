## Module 19 Challenge Alphabet Soup. 

I. Preprocessing methodology to performing neural network via sklearn, tensorflow, and pandas.


### Results 
#### Deliverable 1 requirements.
    'EIN' and 'NAME' drop
    DataFrame
   ![Figure 1](https://github.com/davidhyongae2/network/blob/main/Figure1.png) <br>
    
    The preprocessed data is split into features and target arrays 
    The preprocessed data is split into training and testing datasets 
    The numerical values have been standardized using the StandardScaler() module 
    
   ![Figure 2](https://github.com/davidhyongae2/network/blob/main/Figure3.png) <br>
    
    What variable(s) that are considered the target(s) for your model?

     a. IS_SUCCESSFUL column.

    What variable(s) that are considered to be the features for your model?

     b. Every column except the drop.

    What variable(s) are neither targets nor features, and should be removed from the input data?
  
     c. 'EIN' & 'NAME'


#### Compiling, Training, and Evaluating the Model

The neural network model using Tensorflow Keras contains working code that performs the following steps:
The number of layers, the number of neurons per layer, and activation function are defined  <br>

An output layer with an activation function is created  <br>

There is an output for the structure of the model  <br>
There is an output of the model’s loss and accuracy <br>
The model's weights are saved every 5 epochs <br>
The results are saved to an HDF5 file  <br>

   ![Figure 3](https://github.com/davidhyongae2/network/blob/main/Figure4.png) <br>

   ![Figure 4](https://github.com/davidhyongae2/network/blob/main/Figure5.png) <br>

#### Deliverable 3 Requirements

Noisy variables are removed from features <br>
Additional neurons are added to hidden layers  <br>
Additional hidden layers are added <br> 
The activation function of hidden layers or output layers is changed for optimization  <br>
The model's weights are saved every 5 epochs  <br>
The results are saved to an HDF5 file  <br>

   ![Figure 5](https://github.com/davidhyongae2/network/blob/main/Figure6.png) <br>

How many neurons, layers, and activation functions did you select for your neural network model, and why? <br>
layer1 = 80, layer2 = 30. in order to create a testable set and a training set. <br>
Were you able to achieve the target model performance? <br> 
yes, at an accurancy of 0.7286 <br>
What steps did you take to try and increase model performance? <br>
100 Epoch steps. 50 Epoch and lastly 30 Epoch and period of 5. <br>

#### Summary: 
The model did well at 73% percentage. I recommend a epoch of 30 to reach a model value of 73% percentage. Deep model may be a good model to use if more than one possible nodes of solution can be observed. Neural network is an another trained model to visual other networks of nodes to get to a predicted model or process. 

