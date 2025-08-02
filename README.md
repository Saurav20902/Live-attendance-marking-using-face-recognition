🎓 Face Recognition Based Attendance System
This project is a Face Recognition Based Attendance System developed using Python, OpenCV, and Tkinter. It allows secure registration and attendance logging of students or employees by recognizing their faces via webcam.

📌 Features
📸 Image Capture: Register users by capturing face images.

🔐 Password Protection: Secure the training process with password authentication.

🧠 Face Training: Train a model using OpenCV’s LBPH algorithm.

🎯 Real-Time Recognition: Recognize faces in real-time and log attendance.

🗃️ Data Logging: Save attendance logs as CSV files with date and timestamp.

📅 GUI Interface: User-friendly GUI built with Tkinter.

🔁 Change Password: Option to update the system password.

📂 Folder Structure

├── Attendance/                 # Stores daily attendance CSVs
├── StudentDetails/            # Stores student details CSV
├── TrainingImage/             # Stores captured training images
├── TrainingImageLabel/        # Stores model file and password file
├── haarcascade_frontalface_default.xml  # Haar Cascade model for face detection
├── main.py                    # Main application file
⚙️ Requirements
Python 3.x

OpenCV

Pillow

Pandas

NumPy

Tkinter (usually comes pre-installed with Python)

Install dependencies using:

bash
Copy
Edit
pip install opencv-python pillow pandas numpy
🚀 How to Run
Clone this repository:


git clone https://github.com/your-username/face-attendance-system.git
cd face-attendance-system
Make sure the haarcascade_frontalface_default.xml file is present.

Run the application:


python main.py
