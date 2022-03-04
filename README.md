# FaceDetection
This is a python project that detects faces in an Image or using a Webcam

## Module used : OpenCV
OpenCV is a highly optimized library with focus on real-time applications.It is primarily used to detect objects.

 1)Make sure to install OpenCV before importing it using:pip install opencv-python<br>
 2)Import cv2 library<br>
 3)Since OpenCV already contains many pre-trained classifiers for face, eyes, smile, etc.All these XML files are stored in a folder.We will use face detection model it's XML is attached as 'face_detector.xml' in this github repo.<br>
 4)Load this xml file<br>
 5)Download and save a image that has a face in it and read this img file using cv2.imread() function.<br>
 6)Run the code for detecting faces that is using detectMultiScale() function<br>
 7)To know the face is detected , we drew a rectangle around the face using cv2 library's function cv2.rectangle().<br>
 8)This is final step, you need to export your result as an image file. This image will show the result of face detection. To save a new image file, use a cv2.imwrite() function. After the save is done, you will see "Successfully saved" as your output and your file names face_detected showing detected face will be visible in your directory.<br>

For your reference I have attached an Test image attached named "test.jpeg" and the output/detected image is saved as "face_detected.png".<br>

# Voila!! ✌✌
