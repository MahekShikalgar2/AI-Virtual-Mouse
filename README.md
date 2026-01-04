🖐️ AI Virtual Mouse using Hand Gestures

An AI-powered virtual mouse that allows users to control mouse movements and clicks using hand gestures captured through a webcam.
This project uses Computer Vision techniques with OpenCV and MediaPipe for real-time hand tracking, enabling touch-free mouse interaction.

🚀 Features

🖱️ Move mouse cursor using index finger

👆 Left Click using Index + Middle finger pinch

👉 Right Click using Thumb + Index finger pinch

🎥 Real-time hand tracking via webcam

⚡ Smooth & responsive cursor movement

💻 Works on Windows

🤖 AI-based gesture recognition

🛠️ Technologies Used

Python 3.8 – 3.10 (Recommended)

OpenCV

MediaPipe

PyAutoGUI

NumPy

📂 Project Structure
AI-Virtual-Mouse/
│
├── AIVirtualMouse.py        # Core virtual mouse logic
├── HandTrackingModule.py   # Hand detection & landmark tracking
├── main.py                 # Main execution file
├── README.md               # Project documentation
├── requirements.txt        # Required Python libraries
└── .gitignore              # Ignored files (venv, cache, IDE files)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/AI-Virtual-Mouse.git
cd AI-Virtual-Mouse

2️⃣ Create Virtual Environment (Recommended)
python -m venv .venv
