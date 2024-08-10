# YOLOv8 Video Tracking

This project demonstrates how to use the YOLOv8 model for object tracking in a video using Python and OpenCV.
The script loads a pre-trained YOLOv8 model, processes a video frame by frame, and displays the results with bounding boxes drawn around detected objects.

## Requirements

- Python 3.7+
- OpenCV
- Ultralytics YOLOv8

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/eldan1z/object-detection-yolov8.git
    cd object-detection-yolov8
    ```

2. **Install the necessary Python packages**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the YOLOv8 model**:

    The script uses the `yolov8n.pt` (nano version) model. It will be automatically downloaded when the script is run.

## Usage

1. **Place your video in the project directory**:

    Make sure your video file is in the same directory as the script or provide the correct path to the video file.

2. **Run the script**:

    ```bash
    python yolo_video_tracking.py
    ```

    The script will start processing the video and display the frames with detected objects. Press `q` to stop the video.
