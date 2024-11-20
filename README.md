## Using DoodleNet classifier

This project enables a user to draw an image
and have the DoodleNet model determine the image class. For example, if a user draws a 'tree', the model returns a label and a probability of what it thinks the image is.

## Building Dataset

For learning purposes, I built my own dataset with shapes (circle, triangle, square) using p5.js. 

There is a train_model.js script to import the images, train the model, and output the model to use in another project.