# Object-Detection-Using-Depth-and-Color-Images

Made at iHack - IIT Bombay Software Hackathon 2019

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
