# Image_Segmentation_Oxford_Dataset

### Introduction
This project implements an image segmentation model using the Oxford-IIIT Pet Dataset. The dataset consists of images of 37 breeds of dogs and cats, along with pixel-wise segmentation masks. The goal of this project is to accurately segment pet images into their respective regions using deep learning techniques.

### Features
* **Dataset:** Oxford-IIIT Pet Dataset 37 breeds of pets.Ground truth labels for both classification and segmentation tasks.  
* **Model:** U-Net architecture (or any model you used) for semantic segmentation.  
* **Preprocessing:** Image resizing, normalization, and augmentation.  


### Dataset
The Oxford-IIIT Pet Dataset can be downloaded from the official source. It includes 7,349 images.Pixel-wise segmentation masks indicating the foreground (pet) and background.

### Model Architecture
We used a U-Net based architecture for image segmentation, known for its performance in biomedical image segmentation tasks. The model is trained to classify each pixel into either pet, background, or boundary.

### Training
Loss Function: Categorical Crossentropy with Dice Loss for multi-class segmentation.  
Optimizer: Adam with a learning rate of 0.001.  
Augmentation: Random horizontal flips, scaling, and rotations.  

### Results
The model achieves strong segmentation performance with IoU and Dice scores that demonstrate accurate boundary detection of pets.
