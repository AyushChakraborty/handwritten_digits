# handwritten_digits
using CNN to recognise handwritten digits, using no prebuilt layers from libraries

# Model Architecture
input layer is 28 * 28 dimensional, matching the number of pixels in the image, the following convolutional layer has 14 * 14 size, with a 2 * 2 non-overlapping window used to go through the 28 * 28 dim image, the following convolutional layer is another 14 * 14 block, the one after that is a 7 * 7 block obtained again with a 2 * 2 non-overlapping window used to go through the 14 * 14 dim block, the one after that is another 7 * 7 block, an after that is the final output layer with 10 neurons each for one of the digits. It additionally also passes through a softmax layer to get the probabilities of the digits occurring as the output 
