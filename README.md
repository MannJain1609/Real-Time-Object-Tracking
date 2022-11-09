# Real Time Tracking

In this project, we use the GMM(Gaussian Mixture Models) method for background subtraction and compare it with the inbuilt opencv MoG method. The background subtraction find its applications in real-time tracking.

## Table of contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Technologies](#technologies)
* [Files and Folders](#files-and-folders)
* [Future Extensions](#future-extensions)

## Problem Statement
The objective of this project is to implement the real-time object tracking algorithm using background subtraction
and a Mixture of Gaussians. The implementation is done using the research paper based on "Adpative background mixture models for real time tracking".

## Dataset
I created a video file for this project. It can be found in the repo. it is a 11.5 KB video in the `.mp4` format.

## Technologies
The project uses Python >= 3.5

Other technologies used
* Google Colab / Jupyter Notebook
* OpenCV
* Pillow
* Scipy.stats
* Numpy

## Files and Folders
`Real_Time_Tracking.ipynb`: The main colab file containing the code. It is inside the `src` folder.<br>
`Video File`: It contains the video file used for the project. <br>
`requirements.txt`: The dependencies for the code. They have to be preinstalled.<br>
`Report.pdf`: The understanding of the algorithm and results of the project.
`Reference_Paper` : It contains the research paper used to implement the algorithm. 

## Future Extensions
The project can be extended by able to decrease the runtime and to be adapted to different illuminance, weather conditions in the video clip. 
