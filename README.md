# project1
Real-time AI/ML-based system for detecting and recognizing multiple faces using computer vision .

# Multiperson Facial Recognition System
This Multiperson Facial Recognition System is a real-time AI/ML-powered solution designed to detect and identify multiple individuals simultaneously through live video feeds. It leverages deep learning and computer vision to ensure fast, accurate face detection, recognition, and logging. Ideal for security and surveillance applications, the system supports modular updates, seamless camera integration, and scalable recognition performance.

🚀 Features

- 🔍 Real-time face detection and recognition
- 👥 Supports multiple people simultaneously
- 🎯 High-accuracy recognition using deep learning models
- 📷 Webcam/CCTV camera integration
- 🧠 Modular architecture with training and inference pipeline
- 📈 Logs and stores recognition results for analysis

🧠 Technologies Used

- Python
- OpenCV
- dlib / face_recognition
- TensorFlow / Keras
- NumPy, Pandas
- Flask (for web-based interface)
- SQLite / Firebase (for optional storage)

📂 Folder Structure

📁 multiperson-facial-recognition/
├── dataset/               # Collected face data
├── model/                 # Trained face recognition model
├── src/
│   ├── detect\_faces.py    # Face detection logic
│   ├── train\_model.py     # Model training script
│   ├── recognize.py       # Recognition pipeline
│   └── app.py             # Flask app for live recognition
├── templates/             # HTML templates (Flask)
├── static/                # CSS/JS assets
├── README.md
└── requirements.txt

🛠️ Installation

1. Clone the repository:

bash-
git clone https://github.com/yourusername/multiperson-facial-recognition.git
cd multiperson-facial-recognition
````

2. Install dependencies:

bash-
pip install -r requirements.txt
```

3. Run the application:

bash-
python app.py
```
📸 How It Works

1. Capture and label face images.
2. Train a facial recognition model using embeddings.
3. Use webcam/CCTV feed for real-time detection.
4. Match detected faces with the trained data.
5. Display recognition results on screen or web UI.

📈 Future Enhancements

* 🚪 Access control system integration
* 🧪 Improved accuracy with face embeddings (FaceNet)
* 🌐 Cloud-based storage and dashboard
* 📱 Mobile version for live surveillance

---

## 📬 Contact

For any questions or collaboration ideas, feel free to reach out:

Name:\[Anshika Chaudhary]
Email: \[anshikask05@gmail.com]
LinkedIn:\[https://www.linkedin.com/in/anshika-chaudhary-5115672b7/]

> ⚠️ *This project is currently under development. Full functionality and documentation will be added soon.*


