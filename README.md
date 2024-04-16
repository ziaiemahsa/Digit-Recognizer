# Digit-Recognizer
Digit Recognizer for the MNIST dataset of handwritten digits

Data Description:

- MNIST (https://www.kaggle.com/competitions/digit-recognizer/data) is a subset of a larger set available from NIST
- The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine. (10 classes)
- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
- The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
- The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.
