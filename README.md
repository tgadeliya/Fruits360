# Fruits360
Simple NN for fruits classification based on Fruits360 dataset


### Description
 Implementation of simple nn with convolutional layers and last linear layer with softmax to predict class of the image.

### Some notes
1) Flattener used to change input from conv layers to Fully-Connected\Linear.
2) There are no biases in convolutional layer, because of batch normalization layers. BN has biases inside.
3) Trained on Google Colab
4) There is no need to use grid search, because it is easy to achieve training convergence without much experiments. Just make higher L2 to obtain better result on test.
