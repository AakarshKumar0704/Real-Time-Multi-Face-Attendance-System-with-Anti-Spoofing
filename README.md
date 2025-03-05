# Real-Time-Multi-Face-Attendance-System-with-Anti-Spoofing.
🚀 Overview
The Real-Time Multi-Face Attendance System with Anti-Spoofing is an advanced facial recognition-based attendance solution that ensures accuracy and security by preventing spoofing attacks. This system captures attendance from a live camera feed, supporting multiple individuals simultaneously while incorporating liveness detection to mitigate fraud attempts.


🔥 Features-:

📷 Real-time Face Detection – Identifies multiple faces in a single frame.
🎭 Anti-Spoofing Mechanism – Uses liveness detection to prevent face spoofing with images or videos.
🎯 High Accuracy – Utilizes deep learning models for facial recognition and spoof detection.
📡 Live Camera Integration – Processes real-time video feed for instant attendance marking.
📊 Attendance Management – Stores and tracks attendance records efficiently.

🛠️ Tech Stack-:
Programming Language: Python
Libraries & Frameworks:
OpenCV – For real-time face detection
NumPy – Numerical computations
scikit-learn – Machine learning algorithms
Flask – Backend API for data handling
HTML – Frontend interface for user interaction
Deep Learning Model:
FaceNet, MTCNN for facial recognition
Silent-Face Anti-Spoofing Model -: https://github.com/computervisioneng/Silent-Face-Anti-Spoofing.git

Database: SQLite/MySQL for storing attendance records
🏗️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/AakarshKumar0704/Real-Time-Multi-Face-Attendance-System.git
cd Real-Time-Multi-Face-Attendance-System


2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt


3️⃣ Download Pre-trained Models
Clone the liveness detection model:
bash
Copy
Edit
git clone https://github.com/computervisioneng/Silent-Face-Anti-Spoofing.git
Place the trained model files in the designated directory.


4️⃣ Run the Application
bash
Copy
Edit
python main.py


5️⃣ Access the Web Interface
Open http://127.0.0.1:5000/ in your browser.


📌 How It Works
The system captures real-time video feed and detects multiple faces.
It applies liveness detection to check if the face is real.
If the face passes the spoof detection, the system records attendance.
Attendance data is stored in the database for easy retrieval.


🎯 Future Enhancements
Integration with cloud storage.
Mobile app support for remote attendance.
Enhanced deep learning models for improved accuracy.


📜 License
This project is open-source and available under the MIT License.


🤝 Contributions
Contributions are welcome! Feel free to fork, create pull requests, and submit issues.


📧 Contact
For any queries or collaboration, reach out via aakarshkumar7@gmail.com;.

