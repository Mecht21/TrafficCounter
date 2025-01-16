# Vehicle Detection and Counting with YOLOv8



https://github.com/user-attachments/assets/b7cb863d-efe4-4c84-82a5-3b7bc6675edc



## Overview

This repository contains a Python-based program that utilizes YOLOv8 for real-time detection and counting of vehicles, including cars, motorcycles, trucks, and buses. The program processes a recorded video, detecting each vehicle that exits the track and incrementing a counter for accurate tracking.

## Features

- **Vehicle Detection**: Identifies cars, motorcycles, trucks, and buses in a video.
- **Counting Mechanism**: Counts each vehicle that exits the track and updates the total.
- **Efficient Processing**: Uses YOLOv8 Nano version for optimal efficiency on CPU.
- **GPU Support**: For enhanced performance, the YOLOv8 Large version can be configured and run on a GPU, providing lag-free operation.

## Requirements

- Python 3.x
- YOLOv8 library
- OpenCV
- A recorded video file for processing

## Installation

1. Clone this repository:
     git clone https://github.com/Mecht21/TrafficCounter.git 
2. Create the .venv
3. Install the required dependencies:
   
     pip install -r requirements.txt

## Output

- The program will display the video with detected vehicles and a counter showing the number of vehicles that have exited the track.
- The results can be saved to an output file if needed.

## Acknowledgements

- [YOLOv8](https://yolov8.com/) for the object detection framework.
- [OpenCV](https://opencv.org/) for video processing.
