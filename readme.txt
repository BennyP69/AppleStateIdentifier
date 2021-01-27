Our project relies mainly on sklearn and PyTorch.
The following files are included:

./AppleStateIdentifier/Apple_State_Identifier.ipynb <-- all code here. Preprocessing, training scripts, figures, and utility functions.
./AppleStateIdentifier/data/good <-- good (edible) apple pictures
./AppleStateIdentifier/data/bad <-- bad (inedible) apple pictures
./AppleStateIdentifier/data/mine<-- our own apple pictures to test the CNN with.

* The files should be run in the order: 
	Apple_State_Identifier.ipynb

*GPU is not required. 
*Training takes ~30 minutes.

The apple pictures were downloaded from:
	https://www.kaggle.com/moltean/fruits
	https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification

For training the CNN we relied on the tutorial found at https://www.tensorflow.org/tutorials/images/cnn
