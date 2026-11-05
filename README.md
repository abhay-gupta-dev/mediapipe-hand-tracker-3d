# MediaPipe Hand Tracker 3D

A real-time webcam application that detects up to two hands with MediaPipe and draws a depth-styled hand skeleton. When both hands are visible, it connects corresponding fingertips and wrists with colored lines and translucent faces.

## Requirements

- Python 3.9 or newer
- A webcam
- The MediaPipe hand landmarker model (`hand_landmarker.task`), included in this repository

Install the Python packages:

```bash
python -m pip install opencv-python numpy mediapipe
```

## Run

From the project directory, run:

```bash
python import.py
```

The camera window opens and mirrors the webcam image. Show both hands to see the fingertip bridges. Press **Q** to quit.

The script expects `hand_landmarker.task` in the same directory as `import.py`.

## Project files

- `import.py` — webcam capture, hand landmark detection, and visualization
- `hand_landmarker.task` — MediaPipe hand landmark model

## Upstream project

Repository: [abhay-gupta-dev/mediapipe-hand-tracker-3d](https://github.com/abhay-gupta-dev/mediapipe-hand-tracker-3d)
