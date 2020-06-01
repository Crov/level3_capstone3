# Welcome to my Third and Final Capstone Project.

This purpose of this project is to classify user reviews as positive or negative using NLP.  

## The data
We will use Recurrent Neural Networks, and in particular LSTMs, to perform sentiment analysis in Keras. Conveniently, Keras has a built-in IMDb movie reviews data set that we can use.

## Pad sequences
In order to feed this data into our RNN, all input documents must have the same length. We will limit the maximum review length to 500 words by truncating longer reviews and padding shorter reviews with a null value (0). We can accomplish this using the pad_sequences() function in Keras.

## Train and evaluate our model
We first need to compile our model by specifying the loss function and optimizer we want to use while training, as well as any evaluation metrics we’d like to measure.  
  
Once compiled, we can kick off the training process. There are two important training parameters that we have to specify — batch size and number of training epochs, which together with our model architecture determine the total training time.  
  
Training may take a while, so grab a cup of coffee, or better, go for a run!