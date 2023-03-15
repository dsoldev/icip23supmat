# Modeling and Interpreting 6-D Object Pose Estimation

This page supports the article "Modeling and Interpreting 6-D Object Pose Estimation" submitted for ICIP 2023 with the follwing:
* Iteractive version of Figure 3
* $R_x$ plot that was removed from Figure 3 because of spcae restriction
* The Pose_network results that was removed from the article
* Figure 3 colored by $cos(r1)$ and $cos(r2)$

# Abstract

This work aims to estimate the 6-Degrees of Freedom Pose of an object using simple convolutional neural networks. The problem is that most methods require previous knowledge of the 3D model of the object of interest, which could be unobtainable. We mitigate the problem by simplifying the object’s 3D model to a single and generic primitive solid to create a model that could estimate the pose of unknown objects. Besides that, we study the interpretability of the neural network by using visualization techniques to understand how the network is splitting the high-dimension feature space to reach a Pose estimation.

# Rotation Feature Plot
* Cored by Type: 
* Cored by $R_x$: 
* Cored by $R_z$: 
* Cored by $cos(R_x)$: 
* Cored by $cos(R_z)$: 

# Pose Feature Plot
## Feature Layer
* Cored by Object: 
* Cored by $R_x$: 
* Cored by $R_y$: 
* Cored by $R_z$: 
* Cored by $t_x$: 
* Cored by $t_y$: 
* Cored by $t_z$: 

## Rotation Branch Layer 1
* Cored by Object: 
* Cored by $R_x$: 
* Cored by $R_y$: 
* Cored by $R_z$: 

## Rotation Branch Layer 2
* Cored by Object: 
* Cored by $R_x$: 
* Cored by $R_y$: 
* Cored by $R_z$: 

## Translation Branch Layer 1
* Cored by Object: 
* Cored by $t_x$: 
* Cored by $t_y$: 
* Cored by $t_z$: 

## Translation Branch Layer 2
* Cored by Object: [t_dense2_object](http://vision.ime.usp.br/~dpsoler/pose_networks/resnet50_combined_loss/t_dense2/object)
* Cored by $t_x$: 
* Cored by $t_y$: 
* Cored by $t_z$: 