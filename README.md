# MNIST_neural_network
In this project, I used a neural network to perform handwritten digit recognition based on the MNIST dataset. The dataset consisted of 70,000 images of handwritten digits, with 60,000 samples for training and 10,000 samples for testing. Each image was represented by 28x28 pixels, with a grayscale value ranging from 0 to 255.

To prepare the data for the neural network, I performed several data transformations. First, I reshaped the samples from a 3-D array to a 2-D array, resulting in each image being represented by 784 pixels. I then applied normalization by dividing each grayscale value by 255 and scaling the result by 0.99 + 0.01 to satisfy the range of the sigmoid function. I also used one-hot encoding to convert the labels to floating-point values.

Next, I tuned the model by experimenting with different parameters. I tested the impact of the learning rate by setting it to 0.05, 0.1, 0.2, 0.3, and 0.4 and observed that the accuracy increased from 0.8728 to 0.9254, suggesting that a higher learning rate had a positive impact on performance. I also tested the impact of the number of epochs by setting it from 1 to 5 and found that increasing the number of epochs had a positive relationship with performance. Finally, I tested the impact of the neural network shape by using four different hidden nodes, ranging from 100 to 500, but did not observe a significant impact on performance.

In conclusion, this project demonstrated the effectiveness of using a neural network for handwritten digit recognition and showed that tuning the learning rate and number of epochs can significantly improve performance. However, the impact of the neural network shape on performance was limited in this case. Further research is needed to fully understand the relationship between the neural network shape and performance.
 
