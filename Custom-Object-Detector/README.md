# Custom Object Detection with TensorFlow

## Description
Object detection is a computer vision technique that allows us to identify and locate objects in an image or video. With this kind of identification and localization, object detection can be used to count objects in a scene and determine and track their precise locations, all while accurately labeling them.

![image](https://user-images.githubusercontent.com/69599306/195851262-b07ae4f9-8e0c-423f-b0fd-11c3fd1a7e3b.png)

In this project, we will build a custom object detector using neural networks, and libraries like TensorFlow, Keras, and MatPlotLib. you can run this project on your local machine using Jupyter notebook, or use google colab.

## Installing and Importing Libraries
When running the code, you might run into some issues, where your editor can't find the libraries that are used, in that case, you will need to install them using pip, Like this:

![image](https://user-images.githubusercontent.com/69599306/195856994-ea138689-73e3-4ae1-aecf-83c327bea0ce.png)


## Preparing our dataset
For this project, I have collected my own dataset, consisting of two objects - 
House_keys:

![image](https://user-images.githubusercontent.com/69599306/195852187-d1e1e139-acfc-4186-b3d2-90b2a1b8cfcf.png)
![image](https://user-images.githubusercontent.com/69599306/195852238-415eccb7-8283-4457-a84a-26c2b3edeffc.png)

and TVS_keys:

![image](https://user-images.githubusercontent.com/69599306/195852061-a3f8bc9b-0e1e-4a10-9e74-c531fe034d7c.png)
![image](https://user-images.githubusercontent.com/69599306/195853260-4242e82a-4c55-47b9-be41-c043350032b7.png)

You can find my dataset [here](https://github.com/Adw8/Custom-Object-Detector).

You can also get a dataset from kaggle like [this](https://www.kaggle.com/datasets/antoreepjana/animals-detection-images-dataset)

Now, we will also need [LabelImg](https://github.com/heartexlabs/labelImg), a tool to annotate images, in order to prepare our dataset. You can find a tutorial for LabelImg [here](https://www.altisconsulting.com/insights/labelling-images-for-object-detection-with-labelimg/)

## Training and Testing
We will be training a sequential keras neural network from scratch using our dataset, and the code is provided in the repo, After training comes testing and validation on data that we haven't exposed our model to during training, so it doesn't have any bias.

If you do everything correctly, you can expect an output like this:

![image](https://user-images.githubusercontent.com/69599306/195854634-0ea90fb3-1d12-4c90-9503-86843419b564.png)

## Training and Testing
Following are the training and validation accuracy and loss functions:

![image](https://user-images.githubusercontent.com/69599306/195854672-8e8d2a65-2fa9-4b0a-8b13-3ceca0762b06.png)

![image](https://user-images.githubusercontent.com/69599306/195854720-18c4be4a-7bc5-498c-9825-e8edce1ea48d.png)

### And Voila! We have built a custom object detector successfully!

