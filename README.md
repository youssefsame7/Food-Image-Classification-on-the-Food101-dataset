# Food-Image-Classification-on-the-Food101-dataset
This project covers the entire computer vision process from loading the data to predicting an image class.

# Contents
1. Get data	We're going to be using our own custom dataset of pizza, steak and sushi images.
2. Become one with the data (data preparation)	At the beginning of any new machine learning problem, it's paramount to understand the data you're working with. Here we'll take some steps to figure out what data we have.
3. Transforming data	Often, the data you get won't be 100% ready to use with a machine learning model, here we'll look at some steps we can take to transform our images so they're ready to be used with a model.
4. Loading data with ImageFolder (option 1)	PyTorch has many in-built data loading functions for common types of data. ImageFolder is helpful if our images are in standard image classification format.
5. Loading image data with a custom Dataset	What if PyTorch didn't have an in-built function to load data with? This is where we can build our own custom subclass of torch.utils.data.Dataset.
6. Other forms of transforms (data augmentation)	Data augmentation is a common technique for expanding the diversity of your training data. Here we'll explore some of torchvision's in-built data augmentation functions.
7. Model 0: TinyVGG without data augmentation	By this stage, we'll have our data ready, let's build a model capable of fitting it. We'll also create some training and testing functions for training and evaluating our model.
8. Exploring loss curves	Loss curves are a great way to see how your model is training/improving over time. They're also a good way to see if your model is underfitting or overfitting.
9. Model 1: TinyVGG with data augmentation	By now, we've tried a model without, how about we try one with data augmentation?
10. Compare model results	Let's compare our different models' loss curves and see which performed better and discuss some options for improving performance.
11. Making a prediction on a custom image	Our model is trained to on a dataset of pizza, steak and sushi images. In this section we'll cover how to use our trained model to predict on an image outside of our existing dataset.



# Credits
This project is part of my learning journey — the code is mostly based on [PyTorch for Deep Learning Bootcamp](https://www.udemy.com/share/107tsS3@bXQCmkC6JEhqZaGsI8QA-QqGpq-10c1que0Y5jwXws9BJeFvWy9vEg2lFr1O1V0Pdg==/) by Andrie Neagoi and Daniel Brouke, but the explanations and experiments are my own.
