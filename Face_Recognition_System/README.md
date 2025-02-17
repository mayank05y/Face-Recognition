FACE RECOGNITION SYSTEM

Cam.py: This Python code leverages OpenCV for real-time face detection with a Haar Cascade classifier. It imports OpenCV, loads a face detection model, opens the webcam, and detects faces in a continuous loop. The faces are highlighted with rectangles, and the webcam feed is displayed. The loop stops when 'q' is pressed.

Datacollection.py: This code uses Tkinter for GUI and OpenCV for webcam image capture. It defines a `DataCollectionApp` class for capturing, selecting, and saving images. It allows saving webcam captures or gallery images in a designated folder. The app displays and stores the images with user-provided names.

Frs.py: This script employs OpenCV and face_recognition libraries for real-time face recognition. It loads face images, encodes them, and uses a webcam to capture video. Faces in the video are matched with the encoded images, and recognized faces are highlighted in the webcam feed. The loop exits on 'q' key press.
