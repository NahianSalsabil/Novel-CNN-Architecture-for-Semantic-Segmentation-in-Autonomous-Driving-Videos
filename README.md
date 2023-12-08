Semantic segmentation is an effective computer vision method that precisely categorizes each pixel in an image, making it perfect for high precision object detection, including autonomous driving. In autonomous driving, a vehicle is driven without a driver’s input by employing sensors, cameras, and computers. Semantic segmentation enables vision systems in autonomous vehicles to precisely analyze their surroundings, enabling them to make well-informed choices like spotting and avoiding objects, maintaining lane focus, and interpreting traffic signs.


This work proposes two novel ways for semantic segmentation through modifications
to the pooling layer of a Convolutional Neural Network. The first method uses **wavelet pooling**, which minimizes computational cost while preserving fine features and edges while shrinking the size of the feature maps. This method increases segmentation accuracy in complex scenarios. The second method is **pixel binning** which reduces the resolution of the feature maps while expanding the receptive field and enhances the network’s capacity to gather more contextual information. This method helps to maintain the original image’s fine details as well as reducing the computational costs.


We evaluated our two innovative semantic segmentation approaches on benchmark
dataset named [CAMVID](https://www.kaggle.com/datasets/carlolepelaars/camvid) and found that both are comparable to the state-of-the-art methods in either accuracy and efficiency.
