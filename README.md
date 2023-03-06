# CamSpy

Import the OpenCV library using the "import cv2" statement.
Initialize a VideoCapture object "cap" to capture frames from the default camera (ID 0) using the "cv2.VideoCapture(0)" statement.
Start a while loop that runs indefinitely.
Read a frame from the camera using the "cap.read()" method and assign the frame to the variable "frame".
Display the captured frame in a window named "Camera" using the "cv2.imshow()" method.
Check if the user has pressed the 'q' key by using the "cv2.waitKey(1) & 0xFF == ord('q')" condition. If the 'q' key is pressed, break the loop.
Release the camera using the "cap.release()" method.
Destroy all windows using the "cv2.destroyAllWindows()" method.
In summary, this code captures video frames from a camera and displays them in a window named "Camera" until the user presses the 'q' key to quit the program.
