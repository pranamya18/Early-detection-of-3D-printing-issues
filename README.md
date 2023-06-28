# Early-detection-of-3D-printing-issues

# **Summary**

3D printing is an innovative way to fabricate parts from any 3D geometry model. However, 3D printing is also known to be prone errors. Most of these errors are visible via a close-up camera mounted right near the printer nozzle.

The goal is to predict 1 specific kind of error - under extrusion.

Dataset: https://www.kaggle.com/competitions/early-detection-of-3d-printing-issues/data

The Dataset contains around 100k images of varing sizes

<img width="519" alt="image" src="https://github.com/pranamya18/Early-detection-of-3D-printing-issues/assets/49710041/b60a65ca-2c7c-49eb-bbab-0206902e5c44">

Resized all the images to 512 X 512.

Deployed a Deep Learning model using tensorflow. Built a custom built Convolution Neural Network(CNN) on a pre-trained VGG16 model used for trasfer learning. 
