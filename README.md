# Plant_Species_Classification_CNN

Task:

This project classifies 10 different plant species using 3 block CNN with optimization techniques like data augmentation and shuffling, drop out and Batch Normalization using a small dataset of 1000 images.

Results:

The first convolutional neural network had low validation accuracy. The validation and training accuracy diverged. The high training and low validation accuracy shows overfitting.

To generalize the model, the next model used augmentation and random shuffling on data. This helped avoid overfitting.

Next models used Batch normalization or dropout as well while training which improved both the accuracies.
