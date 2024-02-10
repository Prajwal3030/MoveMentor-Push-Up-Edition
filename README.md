AI Push Up Counter
Overview
This project utilizes computer vision and AI to count push-ups in a given video. The program uses the OpenCV library for video processing and the cvzone library for text rendering. A PoseDetector class is employed to detect key points on the human body, and push-up counting is based on specific hand angles.

Requirements
Python 3.x
OpenCV (pip install opencv-python)
cvzone (pip install cvzone)
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/AIPushUpCounter.git
cd AIPushUpCounter
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
The input video is specified in the cap = cv2.VideoCapture('vid1.mp4') line in main.py. Change the filename to the desired video.
You can adjust the detection and tracking confidence thresholds by modifying the trackCon and detectionCon parameters in the PoseDetector instantiation.
Output
The program generates an output video (output.avi) where the push-up count is displayed in the top-left corner.
