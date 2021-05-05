# Flowers Classification Overview :

- It is real time end to end Neural Networks Project
- Created a Project that identifies different flowers images
- Using Convolutions in neural networks made this model.
- It was built on few techinques such as Data augumentation, Dropouts, Paddings for better outcomes to the model.

# Code and Libaries used

- Python version - 3.8
- IDE - Jupyter Notebook
- Packages - Pandas, Numpy, Matplotlib, Opencv, Tensorflow, Keras, ScikitLearn

# DataSet 

Dataset is taken from tensorflow
- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

# Data Cleaning

- Extracted data from tensorflow
- Resized the image shape
- Created two lists for image shapes and image labels
- Created a numpy array and append those lists to array

# Model Building

First, splitted the data into train and test wise making 20% for testing.
Diving arrays values with 255, because the images are in between 255 of vectors
Now, Using Convolution neural networks model is built
Built the model with 15 epochs and got 98% accuracy, but during evaluation 65%
Here, Used adam optimizer, Sparse Categorical crossentropy and few Conv2D,Maxpooling and Dense layers

- Experiments
To increase this accuracy and evaluation made up mind to tune the model with few techinques like Data Augumentation, Dropouts and padding
After making some experiments on this techniques, with some descent accuracy of 73% and evaluation test of 68%. Really good to see this. 

# Model Performance

- Accuracy : 98 % & evaluation test 65 %
Using techniques:
- Accuracy : 73 % & evaluation test 68 %

Note: Don't miss to check out the model. Thanks

Keep in Touch!! https://www.linkedin.com/in/akshith-kumar-469857135/
