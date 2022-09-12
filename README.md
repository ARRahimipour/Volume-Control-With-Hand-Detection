# Volume Control With Hand Detection

## Video Demo:  https://youtu.be/do08n6gbyPk

## programming by:

- Alireza Rahimipour Anaraki

## Description:

Interaction with the computer is one of the important challenges that the elderly and disabled people face in today's computer world. In recent years, hand gesture recognition has emerged as one of the most natural human-machine interactions in software development, especially to facilitate friendly and flexible human-computer interaction. This paper proposes a system architecture and software configuration to develop a real-time voice-controlled hand gesture on a Raspberry Pi equipped with a camera programmed in Python using the Open-Source Computer Vision (OpenCV) library. The main purpose of the hand gesture recognition system is to communicate between humans and computer systems in order to control voice. According to the experimental results, the hand movement detection system performs well when controlling the voice. This system is able to work in real-time for any individual.

This program can control the sound with the help of libraries available in Python by scanning 2 thumb and index finger.
If the distance between these 2 fingers decreases, the sound decreases, but if the distance between the fingers increases, the sound increases.
The sensor system scans each friend's hand together, but it considers the hand as controllable to enter the system later.

Here we are trying to process a video so that we can control the volume of the device with help of the camera using the tips of our thumb and index finger.

NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Pycaw: Python Audio Control Library

Mediapipe: Mediapipe is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition and provides encapsulation of python. MediaPipe Hand is a high-fidelity hand and finger tracking solution. It uses machine learning (ML) to infer 21 key 3D hand information from just one frame. We can use it to extract the coordinates of the key points of the hand.

### ADVANTAGES:

- Easy to use
- Hassle-free
- Fun to use
- More interactive

### DISADVANTAGES:

- Cant be used for long-distance
- Sometimes not accurate
- Requires a decent camera
- May be confused by two palms

#### Installation-

1] Star and clone the repository to your machine.

2] install `python v3.x`

3] Run the command `pip install mediapipe`

4] Run the command `pip install opencv-python`

5] Run the command `pip install pycaw`

6] Run the command `pip install comtypes`

7] Once all the dependancies have been installed, run the command `python Main.py`
