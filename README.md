# Pedestrian activity recongnition

This repository contains a dataset which was prepared for the master's thesis work "Recognition and prediction of the behavior of road scene dynamic objects based on recurrent neural network"

The dataset contains:
+ videos - video clips of road scenes with pedestrians that were collected from the Youtube;
+ crops - video cuts of pedestrians actions sequences from video clips that were obtained with a Mask R-CNN model;
+ poses - human pose keypoints from crops that were obtained with the MoveNet model.

All objects are divided into 5 classes according to the pedestrian activity:
+ backward - a pedestrian is moving in the opposite direction as a vehicle;
+ forward - a pedestrian is moving in the same direction as a vehicle;
+ left - a pedestrian moves from right to left;
+ right - a pedestrian moves from left to right;
+ on_place - a pedestrian stays in one place.

The dataset contains 100 objects (20 for each class) as train data and 20 objects (4 for each class) as test data