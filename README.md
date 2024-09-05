
# Tennis Analysis System

## Introduction
This project involves analyzing tennis players in a video to measure their movement speed, ball shot speed, and the number of shots. It utilizes YOLO for detecting both players and the tennis ball, and employs CNNs to extract keypoints from the court.

## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)

## Models Used
- **YOLO v8** for player detection
- **Fine-tuned YOLO** for tennis ball detection
- **Court keypoint extraction** using CNNs

## Training
- **Tennis ball detector (YOLO):** See the notebook at `training/tennis_ball_detector_training.ipynb`
- **Tennis court keypoint extraction (PyTorch):** See the notebook at `training/tennis_court_keypoints_training.ipynb`

## Requirements
- Python 3.8
- Ultralytics
- PyTorch
- Pandas
- NumPy
- OpenCV

