# Real-Time Pose Detection Model

This project implements a **Real-Time Pose Detection Model** using OpenCV and Mediapipe. It identifies and classifies human poses from live webcam input, capable of detecting 33 key body landmarks and classifying poses like Warrior II, T Pose, and Tree Pose in real-time.

---
## Features
- Real-time pose detection and tracking via webcam
- Classification of multiple yoga and fitness poses
- Visual skeleton overlay with joint angles
- Efficient performance with Mediapipe optimization
- User-friendly interface with pose labels
---
## Technologies Used
- **Python**: Core programming language
- **Mediapipe**: For detecting and tracking body landmarks
- **OpenCV**: For video capture and image processing
- **NumPy**: For numerical computations
- **Matplotlib**: For visualization and debugging
---
## Installation
### Prerequisites
- Python 3.8 or higher
- Webcam for real-time detection
### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pose-detection.git
   cd pose-detection
   ```
2. Install required packages:
   ```bash
   pip install opencv-python numpy matplotlib mediapipe
   ```
---
## Usage
Run the main script to start pose detection:
```bash
python pose_detection.py
```

The application will:
- Initialize your webcam
- Start real-time pose detection
- Display pose classification results
- Show skeleton overlay on detected poses

Press 'ESC' to exit the application.

---
## Features Details
### Pose Detection
- Uses Mediapipe's pose detection model
- Tracks 33 key body landmarks
- Real-time skeleton visualization

### Pose Classification
Currently supports three poses:
- Warrior II Pose
- T Pose
- Tree Pose

### Angle Calculation
- Calculates joint angles for precise pose classification
- Uses trigonometry for angle measurement
- Real-time angle updates


## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments
- MediaPipe team for the pose detection framework
- OpenCV community for computer vision tools
