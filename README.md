# Neural_Network_Charity_Analysis

## Analysis Overview
Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are numerous columns that contain metadata about each organization. For this Challenge, I identify features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. This requires three parts;

- preprocess the csv data to be run in the neural network model
- compile, train and evaluate the model for its accuracy
- make three attempts to optimize the model by adjusting the preprocessing or by changing various parameters of the model.

## Resources 
- Data Source: charity_data.csv
- Software: Anaconda 4.10.1, kernel mlenv; Jupyter Notebook

## Results
## Data Preprocessing
- The column IS_SUCCESSFUL is the target of the deep learning neural network.
- The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features of the model.
- The columns EIN and NAME are identification information and have been removed from the input data.

# Attempt 1 
![image](https://user-images.githubusercontent.com/70069730/138986016-c41a873e-bb08-49d0-b6f4-d739d81fc6e3.png)

# Attempt 2
![image](https://user-images.githubusercontent.com/70069730/138985693-da4443f7-6ef2-4d6a-9ec6-d88870b55716.png)

# Attempt 3
![image](https://user-images.githubusercontent.com/70069730/138985776-eaddf79d-be92-4eb9-abb0-4072a7606284.png)

## Summary
We unfortunately could not reach an accuracy of 75% in any instance. Our initial model was 53.27%, the first modification made a minor increase to 61.69%, but the other two attempts decreased in accuracy. I would not try running this model for additional epochs, as it would overfit the data. Instead of a deep neural network, I would utilize a Support Vector Machine, or SVM. SVMs would be a better choice for this dataset. 
