MoveMentor Push-Up Edition
Overview
MoveMentor Push-Up Edition is a computer vision-based project that employs artificial intelligence to count push-ups in a given video. The system utilizes OpenCV for video processing and integrates the cvzone library for enhanced text rendering. Key points on the human body are detected using the PoseDetector class, and push-up counting is based on specific hand angles.

Requirements
Python 3.x
OpenCV (pip install opencv-python)
cvzone (pip install cvzone)
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/MoveMentor-Push-Up-Edition.git
cd MoveMentor-Push-Up-Edition
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the program:

bash
Copy code
python main.py
Press 'q' to exit the program.

Configuration
Specify the input video in the cap = cv2.VideoCapture('vid1.mp4') line in main.py. Change the filename to the desired video.
Adjust the detection and tracking confidence thresholds by modifying the trackCon and detectionCon parameters in the PoseDetector instantiation.
Output
The program generates an output video (output.avi) where the push-up count is displayed in the top-left corner.
