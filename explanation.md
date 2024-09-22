# Face Mask Detection
I took the dataset from kaggle with the help of API token in zip format.
Using zipfile module I extracted the two folders which contains with_mask folder and without_mask folder.
Using os module I converted both the folders into list and labeled with_mask as value 1 and without_mask as value 0.
Merged both the with_mask list and without_mask list into a single list.
Image Processing-which contains resizing,converting the image format into 'RGB' and appending both the list in list named data.
Converting image list and label list into numpy arrays.
train test split.
scaling.
Build a convolutional neural network using tensorflow and keras.
Compile the neural network.
Evaluate the model.
Prediction-find the probability of both with_mask and without_mask.
Value: with_mask=1 and without_mask=0.
Using argmax function find out whose probabilty is high&low.
Whoever probabilty is high return the output.
