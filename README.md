# Parking Space Allocator

## Overview
This project explores a computer vision–based approach for detecting
empty and occupied parking spaces using a fixed-camera dataset.

The goal of the project was to understand and analyze a complete
parking occupancy detection pipeline rather than propose a novel model.

## Dataset
The project uses a publicly available parking lot dataset from Kaggle
that includes:
- Parking area images
- A binary mask indicating parking slot locations
- A sample video of the parking lot

Dataset link:
https://www.kaggle.com/datasets/iasadpanwhar/parking-lot-detection-counter

## Approach
- A binary mask is used to identify fixed parking slot locations
- Each parking slot is extracted using bounding boxes
- Individual slots are classified as empty or occupied using image-based features
- The system processes both static images and video frames

## What I Did
- Ran and verified the complete pipeline end-to-end
- Studied how mask-guided slot extraction works
- Analyzed occupancy classification results
- Tested the system on image and video inputs
- Documented strengths and limitations of the approach

## Results
- Successfully detected and classified parking slots as empty or occupied
- Generated processed images and a video with visualized slot status

## Limitations
- Works only for fixed camera angles and layouts
- Sensitive to lighting and weather conditions
- Does not generalize to unseen parking lots without a new mask

## Notes
This project is intended as a learning and analysis exercise.
No claims of real-time performance or production deployment are made.
