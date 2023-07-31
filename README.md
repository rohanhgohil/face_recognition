# Face Recognition Model
- This Python program performs real-time face recognition using OpenCV and face_recognition libraries. It captures video from the webcam and identifies faces of known individuals based on preloaded images of Thalapathy Vijay, Tony Stark, and Elon Musk. When a face is detected, the program draws a box around the face and displays the name of the recognized person below the face.

### Requirements:
- To run this program, you need to have the following libraries installed:
face_recognition
cv2 (OpenCV)
numpy
- You can install these libraries using pip:
```
pip install face-recognition opencv-python numpy
```

### Usage:
- Place the program in a directory and create a photos folder within the same directory.
- Add images of the known individuals (Thalapathy Vijay, Tony Stark, and Elon Musk) to the photos folder. Make sure the image file names match those specified in the program.
- Run the Python script.
- 
### Important Notes:
- The program uses a pre-trained deep learning model from the face_recognition library to generate face encodings for the known individuals. Ensure that the images of the known individuals are clear and recognizable to improve recognition accuracy.
- The program reduces the size of the captured video frame by a factor of 4 to speed up face recognition processing. This may slightly reduce the recognition accuracy but significantly improves the performance.
- The program will continue to recognize faces and display the results until you press the 'q' key on the keyboard.

### Troubleshooting:
- If the program does not recognize faces correctly, consider using better-quality images of the known individuals or adjust the face recognition parameters.
- Make sure your webcam is properly connected and accessible to the program.

### Disclaimer:
- This face recognition program is intended for educational and non-commercial purposes. Be aware of privacy and legal implications when using face recognition technology in real-world applications. Always obtain appropriate permissions and adhere to relevant laws and regulations before deploying such systems.

### Acknowledgments:
- The program uses the face_recognition library, which is built upon the dlib and face_recognition_models packages, and the OpenCV library for image processing and webcam capture. Special thanks to the developers of these libraries for their contributions to the open-source community.
