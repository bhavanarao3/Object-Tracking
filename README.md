# Moving Object Tracking and Curve Fitting

## Objective
This project involves the development of a **Python script** to detect a moving black object in video footage. The script calculates the centroid of the object across the video frames and fits a **parabolic curve** to predict the object's trajectory.

## Key Features

- **Video Processing**:
  - Extracted individual frames from the video footage.
  - Applied **color-based thresholding** to detect the black object in each frame.
  - Calculated and tracked the **centroid** of the object throughout the video.

- **Curve Fitting**:
  - Utilized **Standard Least Squares** to fit a **parabolic curve** through the centroids.
  - Predicted the object's future position by estimating the **y-axis value** when `x = 1000`.

- **Visualization**:
  - Plotted the **trajectory** of the object's centroid across frames.
  - Displayed the **fitted parabolic curve** on a captured frame to visualize the movement pattern.

## Project Structure

- `perception_project1.ipynb`: The Jupyter notebook that contains the entire implementation of the object detection and curve fitting process. The notebook also visualizes the results.

### Video Demonstration

[Video](video.mp4)

## Prerequisites

To run this project, make sure you have the following libraries installed:

- **Python 3.x**
- **OpenCV**
- **NumPy**
- **Matplotlib**

Install the dependencies using pip:

```bash
pip install opencv-python numpy matplotlib



