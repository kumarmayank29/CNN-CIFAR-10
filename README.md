# CNN-CIFAR-10
CNN -CIFAR 10

The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc.with 6000 images per class. There are 50000 training images and 10000 test images. The class labels and their standard associated integer values are listed below. 
0. airplane
1.automobile
2.bird
3.cat
4. deer
5.dog
6.frog
7.horse
8.ship
9. truck
These are very small images, much smaller than a typical photograph, and the dataset was intended for computer vision research.Due to which its really confusing for model to classify between some of entities.For Example: There is a lot of confusion between a CAT and a DOG ie between label 5 and 3 this is already represented in the code as well as in picture shown below-

![Screenshot (975)](https://user-images.githubusercontent.com/64895688/124388845-44455680-dd02-11eb-8026-be06580f8f44.png)


CIFAR-10 is more difficult dataset when compared wrt MNIST and FASHION MNIST due to low quality of images as well as confusing entities which look quite similar in structure. The model gave an accuracy of accuracy of 0.7761(training) and 0.7151(on train)

We are getting an accuracy of 0.7761(Training) and 0.7151(on Testing).This means model is not performing good enough hence we need to do some hyper parameter tuning,to improve our accuracy.
