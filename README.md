Problem Statement: The challenge at hand is to create an intelligent transportation system that can recognize the weather from a single image automatically. This system is essential for maintaining security and safety in inclement weather, helping to avert fatal events like automobile catastrophes, railroad derailments, plane crashes, and ship collisions. Although people can easily determine the weather from photos, developing an autonomous system to do the same is a difficult issue. The objective is to use computer vision techniques to create and deploy a robust classifier that can correctly classify weather conditions from individual photos.

Data Description: The dataset is made up of about 1500 tagged photos that were gathered from several sites like Pexels, Flickr, and Unsplash. It also includes validation pictures. One of five weather categories is applied to each image, and the photographs are then kept in different folders according to the class assigned to each label. On a scale of 0 to 4, the weather categories are ranked, meaning:

0: Cloudy 1: foggy 2: rainy 3: Shine 4: Sunrise The collection contains a variety of sizes and dimensions of photographs that represent various real-world situations. Any weather categorization system must be able to manage this kind of visual variability.

Models that have been implemented: VGG19: This model architecture is renowned for being straightforward and efficient. Its 19 layers—convolutional and fully linked layers among them—have produced state-of-the-art results on a range of image classification applications.

Deep convolutional neural network InceptionV3 is renowned for its accuracy and efficiency. It uses a special architecture with inception modules that enable more efficient use of processing power and enhanced performance.

DenseNet121: DenseNet is a convolutional network with dense connections that establish feed-forward connections between all of the layers. One particular type, DenseNet121, has 121 layers and is well-known for its robust performance on image classification tasks and efficient use of parameters.
