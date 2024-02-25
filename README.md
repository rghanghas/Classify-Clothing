# Classify-Clothing

In this project, I have trained a neural network model to classify images of clothing, like sneakers and shirts. This project uses **tf.keras**, a high-level API to build and train models in **TensorFlow**.

I have used the **Fashion MNIST** dataset which contains 70,000 grayscale images in 10 categories. The images show individual articles of clothing at low resolution (28 by 28 pixels), as seen below:

![image](https://github.com/rghanghas/Classify-Clothing/assets/161168787/20b5fdbf-5e62-47da-a782-3eec967bc0a7.png)

Here, 60,000 images are used to train the network and 10,000 images to evaluate how accurately the network learned to classify images.

Below are the first 25 images from the training set with the class name below each image.

![image](https://github.com/rghanghas/Classify-Clothing/assets/161168787/e6b4a6ae-a112-49bb-88a8-144cd882d86c)

The labels are an array of integers, ranging from 0 to 9. These correspond to the class of clothing the image represents:

[0 - T-shirt/top, 1 - Trouser, 2 - Pullover, 3 - Dress, 4 - Coat, 5 - Sandal, 6 - Shirt, 7 - Sneaker, 8 - Bag, 9 - Ankle boot]

# Models Result

Correct prediction labels are blue and incorrect prediction labels are red. The number gives the percentage (out of 100) for the predicted label.

![image](https://github.com/rghanghas/Classify-Clothing/assets/161168787/70d49d7f-3a74-4469-93d7-e0001a5b1fa9)
