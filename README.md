# Forest_fire_prediction

In this notebook let's see how we can differentiate between an image that shows forest with fire from an image of forrest without fire. To do this I've used CNN. This is part  we'll see how and what errors occured in the successful execution of this project.
# Dataset link : https://data.mendeley.com/datasets/gjmr63rz2r/1/files/2d2c5b94-dc78-4859-8063-0d27e013578b


# Conclusion

###  The dataset is takenfrom the online soure, this is a calssification problem to predict the image is fir or non fir. Firstly we resacale the image with imagedatagenerator after that we load the data with some parameter such as target_size,batch_size etc.Then we install the sequential model in the model we conv2d,maxpooling2d,faltten layer,and finally add dense layer after that we complile the model and then fit the model with 10 epochs, we get arround 98% accuracy score to the model, then create a function to predict the image is fire or non fire, our model is predict the good result of the inputimages.
