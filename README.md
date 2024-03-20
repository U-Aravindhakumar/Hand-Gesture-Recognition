# Hand Gesture Recognition

This project utilizes computer vision techniques and hand tracking to recognize hand gestures and perform corresponding actions using keyboard inputs.

## Installation

1. Install the required dependencies:
   ```bash
   pip install opencv-python mediapipe pyautogui

## Usage

This program tracks hand gestures through your webcam and performs keyboard inputs based on the recognized gestures.

## Input Format

The program takes live video feed from your webcam as input. Each frame captured by the webcam is processed to detect hand landmarks and recognize gestures. The hand landmarks data is represented as a list of landmarks, with each landmark having x, y, and z coordinates normalized to the range [0, 1].

## Example Input

The input consists of live video frames captured by the webcam. No additional input data is required from the user. Your right hand is only use. :raised_hand_with_fingers_splayed: is used to play and pasue the video. :v: is used to degrees the volume.:+1:
:thumbs_lift: is used to rewind the video.

## Dependencies

- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)
- PyAutoGUI (`pyautogui`)

## Contributing

Contributions are welcome! Please follow the guidelines in CONTRIBUTING.md.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, contact your_email@example.com.

## Acknowledgments

- Acknowledgment 1
- Acknowledgment 2
