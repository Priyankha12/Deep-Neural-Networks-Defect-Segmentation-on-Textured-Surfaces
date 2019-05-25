# Deep-Neural-Networks-Defect-Segmentation-on-Textured-Surfaces
In this project, I developed a model to detect defects by Industrial Optical Inspection on Textured Surfaces. 
This problem was modelled as an Image Segmentation task where I found the pixels where the defect occurs in a given image.

The dataset I used is described here: https://hci.iwr.uni-heidelberg.de/node/3616

There are many ways to solve this problem. 
I attempted to solve this using deep learning and the approach that I followed is based on the 
paper on U-Net: Convolutional Networks for Biomedical Image Segmentation.

Project Setup
The project was done using a high-level library Keras. Since the project requires training deep networks, 
I required a GPU. To facilitate this, the project was done using Google Colab. Google Colab provides free GPU runtime 
and can be synced with Google Drive to transfer/load data.
