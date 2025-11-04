# Computer-Vision-Project
👁️ Computer Vision Projects using OpenCV (Google Colab)

This repository contains a collection of Computer Vision mini-projects implemented using OpenCV, NumPy, and Matplotlib — focusing on image processing, shape analysis, 3D vision, motion detection, and in-vehicle vision systems.
All experiments are designed to run seamlessly in Google Colab.

🧩 Modules Overview
1. Binary Shape Analysis

Connectedness, Object Counting, Skeletonization, Fourier Descriptors

Upload a binary image.

Performs connected component labeling, size filtering, skeletonization, and boundary detection.

Computes Fourier shape descriptors and centroids for object recognition.

Example: Analyzing blobs, coins, or leaf shapes.


2. Geometric Shape Detection

Hough Transform, RANSAC, Circle & Ellipse Detection, Iris Localization

Detects lines, circles, and ellipses using the Hough Transform.

Uses RANSAC for robust line fitting.

Locates circular objects like human iris, coins, or wheels.

Includes ellipse fitting using skimage.measure.EllipseModel.


3. 3D Vision & Motion Analysis

Projection, Shape-from-Shading, Stereo Depth, Optical Flow

Upload single or stereo color images.

Demonstrates:

Shape-from-Shading for surface estimation

Stereo Disparity Map for depth reconstruction

Optical Flow for motion analysis

Includes arrow visualization of motion vectors.


4. In-Vehicle Vision: Lane Detection

Roadway, Lane Markings, Hough Transform-based Detection

Detects left and right lanes on road images.

Applies Canny edge detection, ROI masking, and Hough Lines.

Smooths lane boundaries using polynomial fitting.

Output: color-coded lane overlays like ADAS systems.

🧠 Methodological Highlights

Shape-from-Shading & Texture → surface modeling

Hough Transform → parametric line/circle detection

Connected Component Analysis → object labeling

Fourier/Moment Descriptors → shape recognition

Optical Flow → motion field estimation

Lane Detection → in-vehicle vision prototype

🚀 How to Run in Google Colab

Open the .ipynb file of interest in Colab.

Run all cells.

Upload an input image or video when prompted.

Visualize the results (plots, overlays, or 3D surfaces).

🧰 Dependencies
pip install opencv-python numpy matplotlib scikit-image


All projects use:

cv2 – OpenCV (image processing)

numpy – numerical operations

matplotlib – visualization

skimage – advanced shape models (for ellipse/RANSAC)
