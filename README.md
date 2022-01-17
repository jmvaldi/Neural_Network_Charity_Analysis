# Neural_Network_Charity_Analysisi

## Overview
The purpose of this analysis is build a simple neural network model for AlphabetSoup to decide which companies should receive loans. The model wiil predict which applicant (company) will be successful if funded. The dataset that was used 'charity_data.csv' contains more than 34,000 companies that have been previously helped by AlphabetSoup.

## Results

### Data
Looking at the data, the target variable for the analysis is the "IS_SUCCESSFUL" column. Some of the variables that are considered features in the model are "APPLICATION_TYPE" , "AFFILIATION" , "STATUS" etc... When going through the preprocessing data, there were some columns that did not offer revelant data for the model, such as "EIN" and "NAME". 

For the next part the first layer of 8 neurons in the first layer  and 6 in the second layer. Activation function that was implemented was ReLu while the output layer had a sigmoid activation function.

<img width="626" alt="Screen Shot 2022-01-17 at 5 39 19 PM" src="https://user-images.githubusercontent.com/88690258/149844509-2d52d9df-ddaf-40d2-8cc4-46163bee11c3.png">


On the second attemp there were 12 neurons in the first layer and 6 in the hidden layer. The model was kept the same other than the number of neurons.

<img width="627" alt="Screen Shot 2022-01-17 at 5 24 40 PM" src="https://user-images.githubusercontent.com/88690258/149844440-4bd7c5e1-e03b-4538-b376-8d53a152e8cc.png">



From the results we were unable to perform a 75% accuracy score. At the time its not apparent what occured to not get the desired resuls but hvaing a closer look at the number of layers could be beneficial. 
