# Automatic Selfie Capture for Smiling Faces

## Overview

This project is an innovative application that automatically captures selfies when the user smiles. It leverages computer vision and machine learning techniques to detect facial landmarks and recognize smiles in real-time using a webcam.

## Key Features

- **Real-Time Smile Detection**: Utilizes MediaPipe Face Mesh to detect facial landmarks and identify smiles based on the distance between mouth corners.
- **Automatic Selfie Capture**: Takes a selfie automatically when a smile is detected.
- **Sound Notification**: Plays a sound to notify the user that a selfie has been captured.
- **User-Friendly Interface**: Displays the video feed with real-time smile detection in an OpenCV window.

## Technologies Used

- **OpenCV**: For video capture and image processing.
- **MediaPipe**: For facial landmark detection and smile recognition.
- **Python**: The programming language used to implement the application.
- **Winsound**: For playing notification sounds on Windows.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/automatic-selfie-capture.git
    cd automatic-selfie-capture
    ```

2. **Install the required dependencies:**
    ```bash
    pip install opencv-python mediapipe
    ```

## Usage

1. **Run the script:**
    ```bash
    python selfie_capture.py
    ```

2. **Operation:**
    - The webcam will start capturing video.
    - The application will detect your face and track your facial landmarks.
    - When you smile (the distance between mouth corners exceeds a threshold), a selfie will be automatically captured and saved as `selfie.png`.
    - A sound will play to notify you that the selfie has been captured.

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License.
