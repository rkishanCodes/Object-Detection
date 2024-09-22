
# MobileNet-SSD Object Detection

## Overview

This project implements an object detection system using the MobileNet-SSD model. It can process either a video file or a live camera stream to detect and classify objects in real time.

## Features

- Object detection with MobileNet-SSD
- Support for both video files and live camera input
- Adjustable confidence threshold for filtering detections

## Prerequisites

- Python 3.x
- OpenCV
- Numpy

## Installation

1. Clone the repository:

   ```bash
   git 
   cd your-repo-name
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```



## Usage

Run the script with the following command:

```bash
python detect.py --video <path_to_video> 
```

- Replace `<path_to_video>` with the path to your video file. If you want to use the camera stream, leave this argument empty.

### Example

```bash
python Object_Detection.py --video my_video.mp4
```

## Results

The script will open a window displaying the video feed with detected objects highlighted by bounding boxes. Detected objects will be labeled with their class names and confidence scores.
