Hand & Eye Controlled Computer Interaction Toolkit
This project is a Python-based toolkit that uses OpenCV, MediaPipe, and PyAutoGUI to control your computer using hand gestures, facial landmarks, and eye movement — powered by a simple Tkinter GUI.

Ideal for touchless interaction demos, accessibility research, or gesture-based automation tools.

💡 Features
📢 Hand Gesture Volume Control

Controls system volume using distance between thumb and index finger.

Moves volume up/down based on gesture spread.

🖱️ Virtual Mouse Control

Index finger moves mouse cursor.

Clicking by bringing thumb close to index finger.

👁️ Eye-Controlled Mouse

Moves the mouse cursor using eye tracking.

Performs mouse click on blink detection.

📸 Photo Capture

Automatically captures a photo after 50 frames from webcam.

Saves image as captured_photo.jpg and displays it.

🛠️ Technologies Used
OpenCV

MediaPipe

PyAutoGUI

Pillow

Tkinter (GUI)

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/gesture-eye-control.git
cd gesture-eye-control
Install the dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe pyautogui pillow
Note: PyAutoGUI might require additional setup for screen control on macOS or Linux.

🚀 Usage
Run the main script:

bash
Copy
Edit
python your_script_name.py
A simple GUI will appear with four buttons:

Volume Control → Hand-based volume control.

Virtual Mouse Control → Control mouse with finger gestures.

Eye-Controlled Mouse → Move cursor and click using eye movement.

Capture Photo → Takes and displays a webcam photo after a delay.

Press ESC in any OpenCV window to stop that operation.

📷 Screenshots (Optional)
Add screenshots here to demonstrate each feature visually.

👨‍💻 Contributing
Feel free to open Issues or Pull Requests for improvements, bug fixes, or feature suggestions.

📝 License
This project is licensed under the MIT License.

🙌 Acknowledgments
MediaPipe by Google

OpenCV Library

PyAutoGUI Docs

