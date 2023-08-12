# Brain-Tumor-Classification-
This Project was based on comparing the 3 Deep Learning models ie Custom CNN ResNet50 VGG16. 
In this project, we have used Python as our main language in which we have imported numpy, pandas, math, cv2, matplotlib, os, Tensorflow, Kiras.models, Kiras.layers libraries.
Firstly we try to change the images by applying several Image processing techniques firstly we converted our coloured image into grayscale image then we applied Gaussian blur to reduce noise in the image.
We try to crop our image so that the black portion or the black part should be minimized which is called image countering it is a process of identifying structure outlines of object for pattern detection.
Then we apply some techniques to remove the noise from the image like erosion dilation and find contours in threshold image then grab the largest one
This process works as we find the biggest counter then find the extreme points and then we crop the image.
Then after applying the preprocessing we divided our data set into three categories that is training testing and validation our training part was 80% and 10% was testing and 10% was validation.
After that we applied our Keras models in which it includes the convolutional layer, max pooling layer, and then the dropout layer.
And then we run our model to 100 epochs to see how much loss is there and how much accuracy we will get at the end.
And then we do the evaluation part in which we find our accuracies.
And after that we tried to find many other things like relation of epoch numbers with loss relation of epoch numbers with accuracy and then we try to find the confusion matrix also.
