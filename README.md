# Traffic Sign Detection and Recognition

This project aims to detect and recognize traffic signs from a live video feed using computer vision techniques. It utilizes OpenCV for image processing and Python for implementation.

## Features

- Real-time detection and recognition of traffic signs from a webcam feed.
- Identification of common traffic signs such as turn right, turn left, move straight, and turn back.
- Utilizes color thresholding, contour detection, and region-based analysis for sign detection.
- Modular structure for easy expansion and modification.

## Installation

1. Clone the repository:
``` git clone https://github.com/yuvan-s-96/Traffic_Sign_Recognition.git ```

2. Navigate to the project directory:
``` cd Traffic_Sign_Recognition ```

## Usage

1. Run the main script:
`` python traffic sign recognition.py ``


2. The program will start capturing video from the default camera.

3. Detected traffic signs will be displayed with their descriptions overlaid on the video feed.

4. Press 'q' to quit the program.

## Configuration

- Adjust the HSV color range in `findTrafficSign` function to improve detection accuracy for different lighting conditions.
- Modify the `SIGNS_LOOKUP` dictionary in `identifyTrafficSign` function to add or change recognized traffic signs.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request.


