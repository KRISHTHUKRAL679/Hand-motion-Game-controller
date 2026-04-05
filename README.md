# Hand-motion-Game-controller

This project uses computer vision and hand tracking to control a game using hand gestures. It captures video from a webcam, detects hand movements, and translates them into keyboard inputs for game control.

Features
Real-time hand tracking using MediaPipe
Gesture recognition for game control
Keyboard input simulation for game interaction
Support for forward, backward, left, and right movements
Prerequisites
Python 3.9
OpenCV
MediaPipe
PyWin32 (for Windows key simulation)
Installation
Clone this repository:

git clone https://github.com/harshkasat/hand-gesture-game-controller.git
cd hand-gesture-game-controller
Install the required packages:

pip install opencv-python mediapipe pywin32
Usage
Run the script:

python main.py
Position your hand in front of the webcam:

Right hand controls forward/backward movement
Left hand controls left/right movement
Use the following gestures:

Right hand:
Fingers up: Move forward
Fingers down: Move backward
Left hand:
Thumb left of fingers: Move left
Thumb right of fingers: Move right
Press 'e' to exit the program

How it works
The script captures video from the default webcam
MediaPipe is used to detect and track hand landmarks
Based on the position of specific landmarks, gestures are recognized
Recognized gestures are translated into keyboard inputs (W, A, S, D)
These inputs can be used to control games that use standard WASD controls
Customization
You can modify the directkey.py file to change the key mappings or add new gestures and corresponding actions in the main script.

