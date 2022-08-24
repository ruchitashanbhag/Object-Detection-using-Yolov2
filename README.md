# Object-Detection-using-Yolov2

The goal is to emulate the model as described in the paper and train it on the VOC 2012 dataset.

The model works by first splitting the input image into a grid of cells, where each cell is responsible for predicting an arbitrary bounding box. 

Each grid cell predicts a bounding box involving the x, y coordinate and the width and height and the confidence score.
 
A class prediction is also based on each cell.

Yolov2 uses K-means clustering to find the best anchor box sizes for the given dataset by checking for the highest IOU with the bounding box of the object.
 
