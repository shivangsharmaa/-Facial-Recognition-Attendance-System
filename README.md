# Facial-Recognition-Attendance-System
<br>
Attendance Management System that employs face recognition technology to facilitate attendance tracking. It begins by importing essential libraries, including face_recognition, cv2, and datetime, and initializes video capture from the default camera. Known faces and their respective encodings are loaded from image files in a specified directory, establishing a reference for recognition. The script continuously captures frames from the webcam, resizing them for efficient processing. During this loop, it utilizes the face_recognition library to compare the captured faces with known face encodings. When a match is found, the individual's attendance is recorded, and their name and "Present" status are displayed on the video frame. This data, including the name and timestamp, is concurrently written to a CSV file, organized by the current date. The system allows for easy termination by pressing 'q'. Overall, this project provides a basic yet functional solution for real-time attendance management through face recognition, suitable for small-scale educational or organizational applications, while it may require enhancements for more comprehensive use cases and improved recognition accuracy.
<br>
<br>
<h1>Usage</h1>
<br>
The system continuously captures frames from the webcam, recognizing faces based on pre-defined encodings.

When a recognized face is detected, the system marks the individual as "Present" and displays their name on the video frame.

Attendance data is logged in a CSV file with the filename formatted as "YYYY-MM-DD.csv" (e.g., "2023-01-31.csv").

To exit the system, press the 'q' key.
<br>
<br>
<h2>Customization</h2>
<br>
Customize the system by adding known faces and their corresponding encodings to the "C:\photos_project" directory. Ensure that the image filenames match the individuals' names without the ".jpeg" extension.
<br>
<br>
<h3>Data Management</h3>
<br>
Attendance data is saved in CSV files, making it easy to manage and export for various reporting purposes.
