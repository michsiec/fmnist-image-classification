# Building an Image Classification model using TensorFlow  

The goal of this project is to build a neural network model using TensorFlow to recognize different clothes from [Fashion-MNIST dataset](https://www.tensorflow.org/datasets/catalog/fashion_mnist). The dataset comprises 60,000 training images and 10,000 test images.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.

Each training and test example is assigned to one of the following labels:

| Label | Item name |
|---|-------------|
| 0 | t-shirt/top |
| 1 | trouser |
| 2 | pullover |
| 3 | dress |
| 4 | coat |
| 5 | sandal |
| 6 | shirt |
| 7 | sneaker |
| 8 | bag |
| 9 | ankle boot |
