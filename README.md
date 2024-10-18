# Student Loan Risk with Deep Learning

## Overview
The purpose of this project is to predict student loan repayment success using a neural network.

## Functionality

1. **Data Preparation**:
    - **Read and Review Data**: Load the data from a CSV file into a Pandas DataFrame and review its structure.
    - **Define Features and Target**: Identify the features (input variables) and the target (output variable) for the neural network.
    - **Split Data**: Divide the data into training and testing sets.
    - **Scale Data**: Use StandardScaler to normalize the feature data.

2. **Model Creation**:
    - **Sequential Model**: Initialize a Sequential model.
    - **Add Layers**: Add input, hidden, and output layers to the model. The hidden layers use the ReLU activation function, while the output layer uses the sigmoid activation function.
    - **Compile Model**: Compile the model using the binary cross-entropy loss function and the Adam optimizer.

3. **Model Training and Evaluation**:
    - **Fit Model**: Train the model using the training data over 50 epochs.
    - **Evaluate Model**: Assess the model's performance using the test data and calculate loss and accuracy.

4. **Model Usage**:
    - **Save Model**: Save the trained model to a file.
    - **Load Model**: Reload the saved model for making predictions.
    - **Make Predictions**: Use the model to predict loan repayment success on the test data.
    - **Classification Report**: Generate a report showing the precision, recall, and F1-score of the model’s predictions.

## Summary
In summary, this project leverages neural networks to predict the likelihood of student loan repayment success.


