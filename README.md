# Navigation

* ***[Description](#description)***
* ***[How to start?](#how-to-start)***
* ***[Why should you try it?](#why-should-you-try-it)***



# Description

Python application that uses OpenCV library to detect faces in real-time video stream from a camera and frame them with a rectangle. It also provides the functionality to detect faces in pre-recorded video file.

- Python (>=3.9.7)
- OpenCV (>=4.6.0.66)

# How to start?

1. Clone current repository:
```
git clone https://github.com/LeatherDiamond/face_capture.git
```

2. Create and activate virtual environment on your machine:
```
python -m venv environment_name
.\env\Scripts\activate
```

3. Install all the requirements:
```
pip install -r requirements.txt
```

4. In source code by default will be used your device. If you want to detect faces in pre-recorded video-file change line 9:
```
camera = cv2.VideoCapture(path/to/video/file.mp4)
```

5. Run the application:
```
python main.py
```

6. Use "Ctrl+C" to interrupt/exit the application.


# Why should you try it?

Face capture app is a useful tool for anyone who needs to identify and track faces in real-time video streams or pre-recorded video files. It can be used for a wide range of applications, such as security surveillance, marketing analytics, or social media research. With its easy installation and usage, the app is accessible to both novice and experienced Python developers. Its use of OpenCV library ensures that the app is highly efficient and accurate in detecting faces.The app's ability to display real-time video streams with detected faces framed in a rectangle provides a clear visual representation of the detected faces. This feature is especially useful for security surveillance or video analysis applications, where the ability to quickly and accurately identify faces is essential. Overall, if you need to detect and track faces in real-time or pre-recorded videos, Face capture App is a reliable and efficient tool that you should try.
