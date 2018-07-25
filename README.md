# Face-Cap

This project contains the FlickrFace11K data, extracted from [Flickr30K](http://shannon.cs.illinois.edu/DenotationGraph/) image caption dataset, splits for training, validation and testing. The splits are NumPy array files including the name of images in the dataset and their corresponding facial expression labels. Using the label files, you can train a new image captioning model without training a facial expression recognition module. Each label consists of seven binary digits defining 'angry', 'disgust', 'fearful', 'happy', 'sad', 'surprised', and 'neutral', respectively. For example, [0. 0. 0. 1. 0. 0. 0.] is the label of 'happy' samples.
