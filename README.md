# Neural_Network_Charity_Analysis

## Resources

Software:

- Pandas 1.3.2
- Sklearn 0.24.2
- Plotly 5.3.1
- tensorflow 1.14.0

## Overview

We are being given a CSV data set with 34,000 rows and Using the above libraries, create a binary classifier. I will use Neural Network to predict if a charity will be a successful applicant to donations.

## Steps

- Read tbe Data and drop unnecessary fields
- Determine number of values for important fields and create density plots
- Create and bin Columns with too many variables
- Encode and merge the Dataframe
- Use the Standard scaler to prep the data for use in the Neural Network
- Create the Neural network model using Tensor flow (See below for settings and results)

![Neural Network 1](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_1.png?raw=true)

![Neural Network 1 Results](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_1_results.png?raw=true)

- Evaluate the model using created test data and test additional models, for the second model I changed the number of Epochs to 400 and tested with the Tanh activation model

![Neural Network 2](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_2.png?raw=true)

![Neural Network 2 Results](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_2_results.png?raw=true)

-Try a 3rd model where I modified the CSV further and changed the models, and epochs further

![Neural Network 3](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_3.png?raw=true)

![Neural Network 3 Results](https://github.com/CaptCarmine/Neural_Network_Charity_Analysis/blob/main/images/neural_network_attempt_3_results.png?raw=true)

## Results

Looking at the 3 different models which were attempted, it looks that further effort needs to be made at massaging the data, looking at fields which can be more significant in predicting successful outcomes.
