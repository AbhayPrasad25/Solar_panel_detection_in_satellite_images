# Solar Panel Detection in Satellite Imagery
A Deep Learning and Remote Sensing Project
Dataset Link -> https://drive.google.com/drive/folders/1RArZ_uifbSssu8EE7pXAc63iGXwmJd7h?usp=sharing

The final dataset ->https://app.roboflow.com/devansh-mittal-x9qef/solar_panel-tc9aw/1


Rooftop solar panel detection
An object detection project on remote sensing (satellite) images. 
The goal of the project is to detect and create bounding boxes on rooftop solar panels.
This model is designed for Indian terrain. As India is one of the most difficult terrains to create such a project due to various reasons. For example Satellite dataset not available, poor quality of satellite images, very congested infrastructure and availability of solar panels etc.
The dataset problem is solved by creating our own custom dataset by using google maps and a python script.
The images were then labelled by labelimg. A good dataset was formed by performing data augmentation.
This dataset was used to train a deep learning model k/a detection transformer using retinanet as backbone.
This combination can do better detection than a human brain.
The pretrained model was fine tuned and was able to detect solar panels effectively even on very congested buildings.
The model was creating bounding box with 99 to 100 percent confidence.
It was even working well for large solar farms even though it was not trained for it.
Future work:
1.	Video detection
2.	Documentation
3.	Model deployment

#remotesensing
#detection transformer
#retinanet
#rooftop
#solarpanel
