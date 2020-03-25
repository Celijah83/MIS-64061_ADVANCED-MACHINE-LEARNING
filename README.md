# Repository dedicated to coursework and projects for MIS-64061-Adv ML

# Assignment 1:
The purpose of this Assignment was to compare the effect between two and three hidden layers s on the validation accuracy. The MSE loss function was used instead of binary_crossentropy and Tanh activation was implemented instead of the relu.  The main tasks for this assignment was to choose a technique that will improve the model performance. I used the Dropout technique to improve the model. I use IMDB dataset in Keras package for this assignment.

# Assignment 2:
The purpose of this assignment was to modify the IMDB dataset from the previous assignment (Assignment 1). We were told to make a cutoff reviews after 150 words, and restrict the training samples to only 100 while holding the Validate at 10,000 samples. And we were instructed to consider only the top 10,000 words. The main task was to consider both an embedding layer and a pre-trained word embedding. Finally, we were to determine which of the approach did better.  Next, we try changing the number of training samples to determine at what point the embedding layer gives better performance.
