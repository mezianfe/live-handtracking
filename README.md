# Hand Tracking App using OpenCV

## Overview
This project is a simple real-time hand tracking application using OpenCV. It detects and tracks a hand in a webcam feed based on skin color detection. The program applies color filtering in the HSV color space and draws a bounding box around the detected hand.

## Features
- Real-time hand detection using OpenCV.
- Skin color-based segmentation in HSV color space.
- Contour detection to track the hand.
- Draws a bounding box around the detected hand.

## Requirements
Ensure you have Python installed on your system, then install the required dependencies using:

```bash
pip install opencv-python numpy
```

## Usage
Run the script using:

```bash
python handtracking.py
```

### Controls
- Press `Esc` to exit the application.

## Implementation Details
- Captures video feed from the webcam using OpenCV.
- Converts frames to HSV color space for better skin detection.
- Creates a mask for skin color using predefined HSV thresholds.
- Finds contours and draws bounding boxes around detected hands.

## Limitations
- Sensitive to lighting conditions and skin tone variations.
- May detect other objects with similar color to skin.
- Not robust against complex backgrounds.

## Future Improvements
- Implementing more advanced hand tracking using **MediaPipe**.
- Adding gesture recognition for interaction.
- Improving detection using deep learning-based segmentation.



