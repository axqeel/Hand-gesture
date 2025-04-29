# Hands-Free Presentation Controller


## Project Description
An innovative computer vision-based presentation control system that allows users to navigate slides, draw annotations, and interact with presentations using hand gestures through webcam tracking.

## Problem Statement
Traditional presentation controls require physical interaction with keyboard or mouse, limiting presenter mobility and creating barriers for speakers with mobility challenges.

## Solution
Develop a hands-free presentation control system using hand gesture recognition that enables intuitive slide navigation and real-time annotations.

## Technical Details

### Technologies Used
#### Software:
* Languages: Python
* Libraries: 
  - OpenCV (cv2)
  - cvzone
  - NumPy
* Tools: 
  - Computer Vision
  - Hand Tracking

### Implementation

#### Installation
```bash
pip install cvzone
pip install opencv-python
pip install numpy
```

#### Run
```bash
python presentation_controller.py
```

### Project Screenshots
![Slides](https://github.com/user-attachments/assets/fc2b18ce-e961-4684-ae14-bc465723a2dd)
Slide [Navigation- next slide, previous slide]
Thumb up (left) moves to previous slide
Pinky up (right) moves to next slide
These work only when hand is above the gesture threshold line

!![Slides2](https://github.com/user-attachments/assets/40b5fda9-9135-4d61-9000-79e1ebc206d8)
![Slides3](https://github.com/user-attachments/assets/1c6670b2-4228-4d3e-a7aa-2084b5e94c74)
Drawing annotations using hand gesture
Index finger draws on current slide when extended
Two-finger gesture (index and middle) enables drawing mode
Three-finger gesture (index, middle, ring) erases last annotation

![Slides4](https://github.com/user-attachments/assets/371d3995-0fb7-4239-b605-025615a2cdc7)
Erasing annotation using hand gesture
Shows current slide with potential annotations
Displays small webcam view in corner of slide
Allows real-time interaction through hand gestures

### Gesture Controls
* Thumb Up: Previous Slide
* Pinky Up: Next Slide
* Index Finger: Pointer Annotations
* Two Fingers: Draw Annotaion
* Three Fingers: Erase Last Annotation


## Future Enhancements
* Multi-hand support
* More advanced annotation tools
* Cross-platform compatibility

