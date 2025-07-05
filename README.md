DOI
10.5281/zenodo.15812107
# OBJECT-CENTRIC INTERACTIVE VIDEO SUMMARIZATION VIA YOLOV7 AND THRESHOLD-BASED KEY FRAME SELECTION.

The Official Github Repository of "Object-Centric Interactive Video Summarization via Yolov7 and Threshold-Based Key Frame Selection" 

# Download the datasets
  1. TVSUM
  https://www.kaggle.com/datasets/hafianerabah/tvsum-videos
  2.  SUMme
  https://drive.google.com/file/d/1zO-3gWOfyWqXFGxrU1aSkxUGO0UgDwDq/view?usp=sharing

# Features
- YOLOv7-based object detection
- Frame-wise object confidence scoring
- Threshold based key frame selection for generating summary
- Evaluation-ready structure for accuracy and precision analysis
  
# Project Setup

1. Install Dependencies
Make sure you have Python 3.8+ and pip installed.
2. Install the packages provided in the requirement.txt
 ```
pip install -r requirements.txt
 ```
3. Download YOLOv7 Weights
Download the YOLOv7 weights and place them in the weights/ directory:
    ```
    wget https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt -P weights/
    ```
4. Prepare Input Data
Place your video  and csv file in contents You can use .mp4 videos and .csv file sequences.

# Running the Notebook
1.	Open Video_Summarization.ipynb in Google Colab.
2.	Run each cell step-by-step.
3.	The notebook will:
    - Load the model
    - Process video frames
    - Detect objects
    - Score each frame based on detected object confidence
    - Saves key frames using adaptive Threshold
    - Saves the summarized video 
    - Calculate performance metrics such as precision, Recall, F1 score and accuracy

## Output
- Summarized video output with reduced run time This appears  in '/content named as   “final_video.mp4”
## Sample INPUT and OUTPUT Video
-https://drive.google.com/drive/folders/1BJ3F4e9D4kxsT2lyfEhFcSBJtopvGCZt?usp=sharing



