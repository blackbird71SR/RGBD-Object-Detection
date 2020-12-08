# Object Detection Using Depth and Color Images

Made at iHack - IIT Bombay Software Hackathon 2019

## Dataset

RGB-D Object Dataset
http://rgbd-dataset.cs.washington.edu/index.html

The RGB-D Object Dataset is a large dataset of 300 common household objects. The objects are organized into 51 categories arranged using WordNet hypernym-hyponym relationships (similar to ImageNet). This dataset was recorded using a Kinect style 3D camera that records synchronized and aligned 640x480 RGB and depth images at 30 Hz. Each object was placed on a turntable and video sequences were captured for one whole rotation. For each object, there are 3 video sequences, each recorded with the camera mounted at a different height so that the object is viewed from different angles with the horizon.

## The problem Object Detection Using Depth and Color Images solves

1. Can be used for better representation of crowded images in real-life situations like crowd controlling and traffic control
2. Better use of depth information for simultateous image detection in noisy images
3. Better side view prediction probablity
4. Can be used eventually to create state-of-the-art 3D real world object detection by providing faster and precise accuracy.
5. Check Video on GitHub for visualisation.

## Challenges we ran into

1. YOLO fails to extract the relevant information from depth images. So we have to convert it into HHA image format.
2.  It is difficult to combine RGB and depth images to train on single neural network. So we have to train two different neural networks and then combine their results to get more accuracy.

## Technologies we used

- python
- TensorFlow
- keras
- numpy
- Pandas
- YOLO
- darkflow
- Fast CNN
- Google Colab

## Contributors

- Omkar Ajnadkar
- Aditya
- Ankur Konar
- Ratna Priya

## Decription :
### HHA File Extention -
     The HHA file type is primarily associated with HyperHub by Oracle. Internal Tool for editing Oracle based data contained in XLIFF archives.
     
How to open an HHA file?
>You need a suitable software like HyperHub from Oracle to open an HHA file. Without proper software you will receive a Windows message "How do you want to open this file?" (Windows 10) or "Windows cannot open this file" (Windows 7) or a similar Mac/iPhone/Android alert. If you cannot open your HHA file correctly, try to right-click or long-press the file. Then click "Open with" and choose an application. 
