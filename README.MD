# Eye-Blink-Detection
This is a project implementing Computer Vision techniques to detect and count eyeblinks.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites
What things you need to install the software 
* cv2
* immutils
* dlib
* scipy
* numpy

```
pip install -r requirements.txt
```
### Running 
This will run the live feed from webcam.
```
python main.py
```

This will count eyeblinks from given file.
```
python main.py -v test.mp4
```