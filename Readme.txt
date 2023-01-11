Here I will experiment with neural networks, most likely in PyTorch

neural network guessing more than one in the feature at a time is not great
predicting from prediction is even worse

one in the future works pretty nice on average

Paper notes:
choose a constant # epochs, # hidden layers, # prediction values, etc.
Compare the losses and graphs of predictions.

NN->RNN->LSTM->GRU->Transformers

try different optimization andd loss functions

Paper idea:
Comparison of differing RNN structures in order to make time series predictions where input is 1 dimensional(only value predict is given)
fixed things:
    lr
    sequenceLength
    numOut
things to change:
    numLayers
    hiddenSize

problems: normalization

only using the 4 week ahead predition as the output to train on works much better
don't use 2010 as training year because it sucks

multivariate data:
    percent postive tests
    year before
    