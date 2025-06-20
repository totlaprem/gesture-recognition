# gesture-recognition
Hand gesture recognition using MediaPipe and OpenCV
# Gesture Recognition

This project uses OpenCV and MediaPipe to recognize hand gestures in real time using a webcam.

## Features
- Real-time hand tracking
- Gesture counting
- Brightness and volume control using gestures

## Requirements
- Python 3.10 or earlier (not compatible with 3.13+)
- OpenCV
- MediaPipe
- pyautogui
- screen_brightness_control
- pycaw

## Setup
```bash
pip install -r requirements.txt
python recognize.py
gesture-recognition-master/
├── HandTrackingModule/
│   └── hand_tracking_module.py
├── recognize.py
├── README.md
├── requirements.txt
└── ... (other utility files)
