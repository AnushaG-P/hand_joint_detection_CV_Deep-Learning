# Hand Joint Detection Computer Vision:

## Project Overview

This repository comprises three distinct tools/scripts designed for different purposes related to image processing, joint detection, and object detection. Each tool serves a specific function in the domain of medical image analysis and computer vision.

### 1. **DICOM Image Processing Tool (MATLAB)** : 

Objective: Convert DICOM images to JPEG format and organize associated labeling information efficiently.

Implementation: A MATLAB script is utilized to preprocess DICOM files, converting them to JPEG format while systematically managing label file names. This tool is tailored for medical image datasets structured in a hierarchical folder format.

### 2. Finger Joint Detection (Python)

Objective: Detect finger joints in images using OpenCV and scikit-learn.

Implementation:
Allows manual selection of a region of interest (ROI).
Applies image processing techniques to detect contours and their centers.
Utilizes KMeans clustering to identify and locate the joint centers accurately.

### 3. Deep Learning Object Detection using Detectron2 (Python)

Objective: Train an object detection model using Detectron2, a computer vision library developed by Facebook AI Research (FAIR).

Implementation:
Provides code for training an object detection model. 
The weights required for this model can be downloaded from the Detectron2 GitHub repository.
