 Hand Motion Detector

This is a simple real-time Hand Motion Detection project using Python, OpenCV, and MediaPipe. It captures live video through your webcam and detects whether the left hand, right hand, or both hands are visible in the frame.

🛠️ Features

Real-time hand detection using webcam

Differentiates between Left Hand, Right Hand, or Both Hands

Uses MediaPipe's robust hand-tracking model

Highlights hand labels on the video feed

📦 Requirements

Before running the project, install the required Python libraries:

pip install opencv-python mediapipe

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/hand-motion-detector.git
cd hand-motion-detector

Run the Python script:

python project.py

Press q to quit the webcam window.

📁 Files

project.py – Main script that runs the hand detection

🔍 How It Works

Uses cv2.VideoCapture(0) to open the webcam

Processes each frame with MediaPipe's Hand model

Detects hands and classifies them as Left, Right, or Both

Displays the label on the screen with the corresponding position

🧠 Powered By

OpenCV

MediaPipe

Google Protobuf
