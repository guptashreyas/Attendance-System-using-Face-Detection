# Attendance-System-using-
This is a Python-based web application for automated attendance management using facial recognition technology. The system allows users to register their faces, capture attendance through a webcam, and view attendance records through a web interface.

Features
Face Registration: Users can register their faces by capturing multiple images through a webcam.
Automated Attendance: The system uses pre-trained machine learning models to recognize faces and mark attendance automatically.
Web Interface: A simple web interface provides access to attendance records and user management functionalities.
Real-time Updates: Attendance records are updated in real-time as users are recognized.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/facial-recognition-attendance.git
Navigate to the project directory:
bash
Copy code
cd facial-recognition-attendance
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Start the application:
bash
Copy code
python app.py
Access the web interface through a browser at http://localhost:5000/.

Register new users by navigating to the "Add User" page and capturing their images.

Initiate the attendance capture process by clicking on the "Start Attendance" button on the home page. Ensure that a webcam is connected and functioning properly.

View attendance records on the home page. Records are automatically saved to a CSV file in the Attendance directory.

Technologies Used
Python
Flask
OpenCV
scikit-learn
NumPy
pandas
Contributors
Your Name
Contributor 1
Contributor 2
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
The Haar cascade classifier for face detection is sourced from OpenCV.
Training data for face recognition is provided by the users during registration.
Demo
Link to Demo Video (if available)
