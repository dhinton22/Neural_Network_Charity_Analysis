# Neural_Network_Charity_Analysis

## Overview
Using Machine Learning and Neural Networks for this project, I used the features in the dataset to create a binary classifier that will help to predict if the applicants that will be funded by a Charitable organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the following 3 steps:

    -- Preprocessing the data for the neural network
    -- Compile, Train and Evaluate the Model
    -- Optimizing the model
    
    
## Results
# Data Preprocessing

    -- Variable that was considered as the target for my model: IS_SUCCESSFUL Column
    -- Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
    -- Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

# Compiling, Training and Evaluating the Model
  The number of neurons, layers, and activation functions I selected for my neural network model:

    -- For my neural network model I had 2 hidden layers. My first layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."
    
    ![image](https://user-images.githubusercontent.com/103547108/188460748-343ee1ea-c3b4-412b-9ce8-9e23f2102571.png)

Was the model able to achieve the target model performance?
    -- The model was not able to reach the target 75%. The accuracy for my model was 65%.

![image](https://user-images.githubusercontent.com/103547108/188460953-0f4dd4dc-8e20-465a-9005-13f0b3a70b30.png)

The steps taken to try and increase model performance

Attempt 1: Removed additional feature, that is the 'USE_CASE' column. Rest of the model components stayed the same, however model accuracy was only 56%.

![image](https://user-images.githubusercontent.com/103547108/188461435-dae66b4f-5058-482a-8c7e-7164c904f8f5.png)

Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy went down again, this time it was 44%.

![image](https://user-images.githubusercontent.com/103547108/188461665-4aa9918a-dc8e-478c-b965-1e67de6dc68d.png)

Attempt 3: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy of the model went up even more to 65%.

![image](https://user-images.githubusercontent.com/103547108/188462053-05d1d4dd-c9c1-46b4-a3a7-12ceb6dd178a.png)
