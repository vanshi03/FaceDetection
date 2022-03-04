# FaceDetection
This is a python project that detects faces in an Image or using a Webcam

##Module used : OpenCV
OpenCV is a highly optimized library with focus on real-time applications.It is primarily used to detect objects.

<ul>
  <li>1)Make sure to install OpenCV before importing it using:pip install opencv-python</li>
  <li>2)Import cv2 library</li>
  <li>3)Since OpenCV already contains many pre-trained classifiers for face, eyes, smile, etc.All these XML files are stored in a folder.We will use face detection model it's XML is attached as 'face_detector.xml' in this github repo.</li>
  <li>4)Load this xml file</li>
  <li>5)Download and save a image that has a face in it and read this img file using cv2.imread() function.</li>
  <li>6)Run the code for detecting faces that is using detectMultiScale() function</li>
  <li>7)To know the face is detected , we drew a rectangle around the face using cv2 library's function cv2.rectangle().</li>
  <li>8)This is final step, you need to export your result as an image file. This image will show the result of face detection. To save a new image file, use a cv2.imwrite() function. After the save is done, you will see "Successfully saved" as your output and your file names face_detected showing detected face will be visible in your directory.</li>
</ul>

For your reference I have attached an Test image attached named "test.jpeg" and the output/detected image is saved as "face_detected.png".

#Voila!! ✌✌
