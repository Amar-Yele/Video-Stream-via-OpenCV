# Video-Stream-via-OpenCV
Real Time Video Stream Using OpenCV with Java

## Title: Real-Time Video Stream Analysis Application

### Description:
This project is a real-time video stream analysis application built using Java, JavaFX, and OpenCV. The application processes video streams to detect faces, pedestrians, and moving objects, with capabilities to record the processed video.

### Features:

Face Detection: Uses Haar cascade classifiers to identify faces.
Pedestrian Detection: Detects pedestrians using Haar cascades.
Motion Tracking: Applies background subtraction to track moving objects.
Video Recording: Saves the video with annotations to a specified file.
Installation:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/yourrepository.git
Set up dependencies:

Ensure you have Java JDK 21 and JavaFX SDK 21.0.4 installed.
Configure your IDE to include the JavaFX libraries and OpenCV native libraries.
Build and Run:

Compile and run the application from your IDE or using command line:
bash
Copy code
javac -cp "path/to/opencv.jar;path/to/javafx-sdk/lib/*" com/openCV/VideoStreamMain.java
java -cp "path/to/opencv.jar;path/to/javafx-sdk/lib/*;." com.openCV.VideoStreamMain

### Usage:

Launch the application and click Start to begin processing the video stream.
Use Stop to end the session and save the recorded video.
Contributions:
Feel free to fork the repository and make improvements. Pull requests are welcome!

#### License:
This project is licensed under the MIT License.
