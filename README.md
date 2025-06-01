# AI-Real-Time-Face-Detection-System

A robust, real-time face detection implementation using OpenCV's Haar Cascade classifier. Suitable for both development and educational purposes.

## Features

- 🚀 Real-time face detection from webcam feed
- ⚙️ Tunable detection parameters for optimal performance
- 📊 Live face counter display
- 📝 Available in both Python script and Jupyter Notebook formats
- ✅ Includes pre-trained Haar Cascade model

## Installation

### Prerequisites
- Python 3.7+
- OpenCV 4.0+

### Setup
## Clone repository
git clone https://github.com/your-username/face-detection.git
cd face-detection

## Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## Install dependencies
pip install -r requirements.txt
### Usage
## Command Line Interface
python detect_faces.py \
    --scale 1.3 \
    --min-neighbors 4 \
    --thickness 2
### Jupyter Notebook
jupyter notebook face_detection.ipynb
Press ESC to terminate the application.
### Performance Notes
## For optimal performance:

Ensure good lighting conditions

Use frontal face orientation

Adjust scale and min-neighbors based on:

Higher scale → Faster but less accurate

Higher neighbors → Fewer false positives
