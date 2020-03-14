# LSTM
This contains Mini Case studies or Projects based on mainly LSTM

    In this project i tried to perform Sentiment Analysis on a imdb movie dataset which consists of 25,000 Reviews for training and 25,000 reviews for testing.
    We started with simply 
        1)Loading the dataset
        2)Imorting required Libraries
        3)Preprocesing the Dataset to carry out further Analysis
        
    I Tried Padding to equalise each row to same length
    Used LSTM
    Also tried LSTM with dropout (to avoid Overfitting)
    Double Dropout (Droput in Layers and also in LSTM layer)
    LSTM wth CNN of 1 D
    LSTM wth CNN of 1 D and flatten layer
    Chaning Batch Size for understanding variation in accuracy
    
    Question:What else can be done?
    Answer: I can try to see the change in accuracy observed due to change in:
        1)Activation function
        2)Batch size during training
        3)Optimiser functions like :adam, sgd
        4)Adding or removing more hidden layers and Dense layers
        5)Adding or removing : Drop-Outs
        6)Adding Flatten layer
        7)changing Filter size in 1-D CNN
        8)Changing Embedded Vector Length
            
