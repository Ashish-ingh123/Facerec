A robust face recognition system using OpenCV and MediaPipe for face detection and GFPGAN for face restoration. This project accurately detects and recognizes faces from images or live video feeds, making it ideal for real-time applications.

Features
Real-time face detection and recognition using OpenCV and MediaPipe.
High-quality face restoration using GFPGAN.
Supports both image and video input.
Easy-to-use and customizable.
Technologies Used
Python
OpenCV
MediaPipe
GFPGAN
NumPy
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/face_recognition_system.git
cd face_recognition_system
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Download pre-trained Haar cascade models from OpenCV:

ruby
Copy
Edit
wget https://github.com/opencv/opencv/raw/master/data/haarcascades/haarcascade_frontalface_default.xml
wget https://github.com/opencv/opencv/raw/master/data/haarcascades/haarcascade_eye.xml
Usage
Run the face recognition script:

nginx
Copy
Edit
python face_recognition.py
To use a custom image:

arduino
Copy
Edit
python face_recognition.py --image path/to/image.jpg
To use live video from a webcam:

css
Copy
Edit
python face_recognition.py --video 0
Configuration
Update the configuration settings in config.json to customize input sources, model paths, and other parameters.
Examples
Real-Time Face Recognition


Image Face Recognition


Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
