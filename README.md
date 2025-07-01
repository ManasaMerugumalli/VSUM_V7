# Object Detection with YOLOv7

This project demonstrates object detection using the YOLOv7 architecture. It includes detection of objects in images frames and calculates frame-wise confidence scores for video summarization.

# Features
- YOLOv7-based object detection
- Frame-wise object confidence scoring
- Integration-ready for keyframe scene summarization
- Evaluation-ready structure for accuracy and precision analysis
# Project Setup

1. Install Dependencies
Make sure you have Python 3.8+ and pip installed. Then run:
pip install -r requirements.txt
2. Download YOLOv7 Weights
Download the YOLOv7 weights and place them in the weights/ directory:
    ```
    wget https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt -P weights/
    ```
3. Prepare Input Data
Place your video  and csv file in contents You can use .mp4 videos and .csv file sequences.

# Running the Notebook
1.	Open OBJECT_DETECTION.ipynb in Google Colab.
2.	Run each cell step-by-step.
3.	The notebook will:
    - Load the model
    - Process video frames
    - Detect objects
    - Score each frame based on detected object confidence and Threshold
    - Saves the summarized video 
    - Calculate metrix
## Output
- Summarized video output with reduced run time This appears  in '/content named as   “final_video.mp4”


