# Virtual-Keyboard

A Python-based Virtual Keyboard built with OpenCV, CVZone, and Pynput, allowing users to type using hand gestures detected from a webcam.

 ### Features

-  Hand Tracking using CVZone’s HandDetector

-  Gesture Recognition – press keys by bringing your thumb and index finger together

- On-Screen Keyboard with hover + click highlights

- Supports alphabets, numbers, space, enter, and backspace

- Option to display typed text on screen

### Tech Stack

- Python

- OpenCV – for computer vision

- CVZone – for easy hand detection

- Numpy – for distance calculation

- Pynput – for simulating keyboard presses

## Installation

### Clone the repo:

git clone https://github.com/your-username/virtual-keyboard.git

cd virtual-keyboard


### Install dependencies:

pip install opencv-python cvzone numpy pynput


### Run the project:

python main.py


### How It Works

- Webcam captures video input

- CVZone detects hand landmarks

- If index finger hovers on a key → button highlights

- If thumb + index finger distance < threshold → key press triggered

- Keys are simulated with pynput.keyboard.Controller

### Demo
  ![Virtual Keyboard](https://github.com/user-attachments/assets/c45075c7-f2bf-48f4-9370-6ce68098ddb9)

