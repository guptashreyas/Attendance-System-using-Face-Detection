# Attendance-System-using-Face-Detection

This is a Python-based web application for automated attendance management using facial recognition technology. The system allows users to register their faces, capture attendance through a webcam, and view attendance records through a web interface.

Features
Face Registration: Users can register their faces by capturing multiple images through a webcam.
Automated Attendance: The system uses pre-trained machine learning models to recognize faces and mark attendance automatically.
Web Interface: A simple web interface provides access to attendance records and user management functionalities.
Real-time Updates: Attendance records are updated in real-time as users are recognized.
## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your_username/facial-recognition-attendance.git
2. **Navigate to the project directory:**

   ```bash
   cd facial-recognition-attendance

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt

Usage
## Usage

1. **Start the application:**

   ```bash
   python app.py

2.Access the web interface through a browser at http://localhost:5000/.

3.Register new users by navigating to the "Add User" page and capturing their images.

4.Initiate the attendance capture process by clicking on the "Start Attendance" button on the home page. Ensure that a webcam is connected and functioning properly.

5.View attendance records on the home page. Records are automatically saved to a CSV file in the Attendance directory.

Technologies Used
Python
Flask
OpenCV
scikit-learn
NumPy
pandas

Acknowledgements

->The Haar cascade classifier for face detection is sourced from OpenCV.
->Training data for face recognition is provided by the users during registration.
