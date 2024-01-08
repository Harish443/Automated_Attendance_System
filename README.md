**Face Recognition Attendance System using Flask**

This project is a simple face recognition attendance system implemented using Flask, OpenCV, and face_recognition library. The system captures live video feed from a webcam, recognizes faces, and tracks attendance by marking 'In' and 'Out' times for recognized individuals.



Live video feed with face recognition
Automatic tracking of attendance (In and Out times)
CSV file generation for attendance records
Web-based user interface for monitoring and managing attendance data
Prerequisites

**Before running the application, make sure you have the following installed:**

Python 3.x
Flask
OpenCV
face_recognition

-You can install the required Python packages using the following command:

bash
Copy code
pip install Flask opencv-python face_recognition
Installation

-Clone the repository:
bash
Copy code
git clone https://github.com/your-username/face-recognition-attendance.git
cd face-recognition-attendance

File Structure

app.py: Main Flask application file.
templates/: HTML templates for web pages.
static/: Static files (CSS, images).
face/: Directory to store known face images for recognition.
Attendance.csv: CSV file to store attendance records.
