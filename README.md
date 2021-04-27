# NeuralNet-HandwrittenTextRecognition
This project trains a convoluted neural network to identify handwritten texts. You can upload a picture of a letter and the CNN will predict what letter it is.

# Don't want to train?
If you don't want to train the model (or your computer doesn't have the resources right now) then you can use the model_hand.h5 file. The hdf5 file containes the weights for the model to a training accuracy of about 97%
### How to run the pre-tained file
On loading the .ipynb file on Jupyter Notebook, Run all the code blocks one by one until you get to the section 'Creating and Training CNN'. In this section, you can skip the first 3 code blocks of this section - this is because this code blocks are to train the model, but you don't want to do this. Jump straight to the 4th code block of this section that starts with "#load model". Run this block and all blocks after it.


#### Credit
Credit to the team at Data Flair who did a pretty solid job of explaining the entire process:
https://data-flair.training/blogs/handwritten-character-recognition-neural-network/

They inspired this project, and with a few tweaks here and there, we got it!
