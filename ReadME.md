## Module 19 Challenge Alphabet Soup. 

I. Neural networks via sklearn, tensorflow, and pandas processing.


# Step 2: Results 
#### Deliverable one requirements.
    'EIN' and 'NAME' drop
    DataFrame
   ![Figure 1](https://github.com/davidhyongae2/network/blob/main/Figure1.png) <br>
    
    The preprocessed data is split into features and target arrays 
    The preprocessed data is split into training and testing datasets 
    The numerical values have been standardized using the StandardScaler() module 
    
   ![Figure 2](https://github.com/davidhyongae2/network/blob/main/Figure3.png) <br>
    
    What variable(s) are considered the target(s) for your model?

     a. IS_SUCCESSFUL column.

    What variable(s) are considered to be the features of your model?

     b. Every column except the drop.

    What variable(s) are neither targets nor features and should be removed from the input data?
  
     c. 'EIN' & 'NAME'

# Step 3: Compiling, Training, and Evaluating the Model

The neural network model built with TensorFlow Keras includes functional code that performs the following steps:

1. The number of layers, the number of neurons per layer, and the activation functions are defined.
2. An output layer with an activation function is created.
3. The structure of the model is displayed.
4. The model's loss and accuracy are provided.
5. The model's weights are saved every five epochs.
6. The results are stored in an HDF5 file.

   ![Figure 3](https://github.com/davidhyongae2/network/blob/main/Figure4.png) <br>

   ![Figure 4](https://github.com/davidhyongae2/network/blob/main/Figure5.png) <br>

#### Deliverable 3 Requirements

- Noisy variables are removed from features.  
- Neurons and hidden layers are added.  
- Activation functions are optimized.  
- Model weights are saved every five epochs.  
- Results are stored in an HDF5 file.  

   ![Figure 5](https://github.com/davidhyongae2/network/blob/main/Figure6.png) <br>

How many neurons, layers, and activation functions did you select for your neural network model, and why? <br>
layer1 = 80, layer2 = 30. to create a testable and training set. <br>
Were you able to achieve the target model performance? <br> 
yes, at an accuracy of 0.7286 <br>
What steps did you take to try to increase model performance? <br>
100 Epoch steps. 50 epochs, and lastly 30 epochs and a period of 5. <br>

# Summary: 
The model achieved a performance rate of 73%. I suggest utilizing 30 epochs to achieve optimal results. A deep model is advantageous when multiple solution nodes are present, and a neural network can effectively visualize these nodes to enhance predictive accuracy.

