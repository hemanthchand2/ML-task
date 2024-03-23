# ML-task
IQ gateway interview task 
# INTRODUCTION
This project seeks to assess the intensity of emotions within text utilizing a range of methodologies and models. We will investigate statistical models, lexicon-based strategies, and deep learning techniques to forecast the intensity of four primary emotions: anger, fear, joy, and sadness, present in textual data.

# DATASET
Utilizing a dataset comprising tweets annotated with the intensity levels of four emotions - anger, fear, joy, and sadness, we partition the dataset into training, validation, and test subsets for the purpose of model development and assessment.

# RESULTS
VADER: RMSE on Test Set: 0.757
    Lexicon-based Approach: Accuracy: 0.423
    Linear Regression:
        Anger: RMSE on Test Set: 0.235
        Fear: RMSE on Test Set: 0.210
        Joy: RMSE on Test Set: 0.227
        Sadness: RMSE on Test Set: 0.270
    LSTM: Test Loss: 0.004
