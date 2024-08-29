# Fisheye Camera Calibration with OpenCV
This project demonstrates how to perform fisheye camera calibration using OpenCV to correct lens distortion and achieve accurate imaging results. By calibrating a fisheye camera, we can remove the significant distortion introduced by wide-angle lenses, making the images suitable for various computer vision applications.

## Overview
Fisheye lenses offer a wide field of view but introduce notable barrel distortion, which can compromise the accuracy of image analysis. This project utilizes OpenCV's fisheye calibration tools to:
- Calibrate a fisheye camera using a set of images with a known checkerboard pattern.
- Remove lens distortion and produce rectified (undistorted) images.
- Calculate and visualize the reprojection error to assess calibration accuracy.
- Optimize the calibration process by debugging and excluding high-error images.

## Potential Applications
- **Virtual Reality (VR) and Augmented Reality (AR):** Ensures accurate object placement and alignment by correcting lens distortion.
- **Robotics and Autonomous Vehicles:** Provides precise mapping and localization by undistorting fisheye images used for navigation and obstacle detection.
- **360-Degree Photography and Videography:** Improves the quality of panoramic images and videos by correcting fisheye lens distortion.
- **Security and Surveillance:** Enhances image accuracy in wide-area surveillance, facilitating better analysis and anomaly detection.
