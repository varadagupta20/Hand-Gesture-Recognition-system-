# Hand-Gesture-Recognition-System-
This project focuses on hand gesture recognition using computer vision to enhance driving safety. The system detects hand gestures on a steering wheel to determine the appropriate driving mode, ensuring that the car responds according to the detected hand positions. The trained model uses an XML file capturing four types of hand gestures.

## Features

No Hands on Steering Wheel: If no hands are detected on the steering wheel, the car's brakes are applied slowly.

One Hand on Steering Wheel: If one hand is detected, the car can be driven up to a certain speed limit for safety purposes.

Both Hands on Steering Wheel: If both hands are detected, the driver can drive at any speed, as this is considered the safest mode.

### Prerequisites
Python 3.x

OpenCV

NumPy

