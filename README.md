# Fashion-MNIST
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix.
For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below. 

# The Sole purpose of doing this project was to create a code to be run in Colab TPU
Importing Dataset and Libraries
Loading data
Checking shape
Plotting to visualize the data
Reshaping Data
Data Pre-processing using Image Data Generator
Creating a CNN model
Compiling the model
Checking Accuracy
