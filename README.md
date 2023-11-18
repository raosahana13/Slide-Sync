# Slide-Sync: Gesture-Controlled Presentation Tool

## Overview
The Slide-Sync project introduces a Gesture-Controlled Presentation Tool that utilizes OpenCV and the Hand Detector module from the cvzone library for real-time hand tracking. This tool allows presenters to control the flow of a presentation and make annotations through intuitive hand gestures, eliminating the need for traditional input devices like keyboards and mice.

## Features
- **Real-time Hand Tracking:** The tool employs OpenCV and the cvzone Hand Detector module to track the presenter's hand in real-time.
- **Gesture-Controlled Navigation:** Presenters can navigate through presentation slides using simple hand gestures, such as swiping left or right.
- **Annotation Support:** The tool enables presenters to make on-the-fly annotations on slides by using specific hand gestures, enhancing the interactive presentation experience.
- **User-Friendly Interface:** The interface is designed to be intuitive, allowing presenters to seamlessly integrate gesture control into their presentations.

## Requirements
- **Python 3.x**
- **OpenCV**
- **cvzone**
  
## Getting Started
**Clone the Repository:**
   ```bash
   git clone https://github.com/raosahana13/slide-sync.git
   cd slide-sync

#Install Dependencies:**
pip install opencv-python
pip install cvzone

#Download Presentation Images

#Run the Presentation Tool:
Execute the Python script to start the presentation tool through Pycharm

##How to Use
Slide Navigation:

Swipe left gesture: Move to the previous slide.
Swipe right gesture: Move to the next slide.

Annotation:
Raise one finger and tap: Start/stop annotation mode.
While in annotation mode, draw on the slide by moving your index finger.
Quit:Press 'q' to exit the presentation tool.

##Notes
Adjust the gestureThreshold variable in the code to set the threshold for detecting hand gestures.
Feel free to customize the code to suit your preferences or integrate additional features.
Enhance your presentations with this innovative Gesture-Controlled Presentation Tool!

