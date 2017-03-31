Self-Driving Car Nanodegree
Project 1: Finding Lane Lines on a Road

\Victor Roy
Last Updated: March 28, 2017

Prerequisites:

Python 3.x
OpenCV
moviepy
matplotlib
pandas
numpy
Jupyter Notebook

Description:

The notebook and writeup included in this repository were created to satisfy the
 requirements for Udacity's Self-Driving Car Nanodegree's First Project.

In the project, we are asked to create a pipeline that can read in a video and
overlay that video with lines approximating the current lane's markers.

The project uses several image processing algorithms found within the OpenCV
python library, including Canny Edge Detection, Hough Line Transform and
Guassian Blurring.

In additon to tuning parameters for those functions, this exercise required
processing, extrapolating and smoothing the output generated from the Hough Line
 Transform. The bulk of this work is done in the process_lines() function found
In[3]

The original repository for this project may be found at:
https://github.com/udacity/CarND-LaneLines-P1

\V
