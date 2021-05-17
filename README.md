# Deep-Learning

This project aims to use deep learning techniques to classify the different traffic signs using the German
Traffic Sign Recognition Benchmark dataset. The intent of this project is that to achieve level 5 autonomy,
vehicles must understand and follow all traffic signs/rules. The report compares the performance of
different models that were used to classify the traffic sign accurately. Before model building, the dataset
underwent exploratory data analysis through class identification to view the potential impacts of class
imbalance. Also, the data went through a process of augmentation and image pre-processing to improve the
various models and this was a process that was revisited many times to increase model accuracy. The
Convolutional Network (CNN) model was found to generate the best results with data augmentation of the
images giving an accuracy of approx. 94%. Further, transfer learning with MobileNet V2 was explored
which resulted in a test accuracy of 96.8%. Object detection was also performed to identify and track precise
locations of an object in the image, as well as accurately labeling them. The rest of this report discusses our
methods and implementations as well as our results and any other miscellaneous information needed to be
understood through the scope of our project.
