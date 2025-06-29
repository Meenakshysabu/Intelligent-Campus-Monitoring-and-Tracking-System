#🎓 Intelligent Campus Monitoring and Tracking System

##📌 Project Overview
"Intelligent Campus Monitoring and Tracking System" is our mini project—an AI-powered solution designed to enhance campus security and automate student tracking through real-time facial recognition. It replaces manual and RFID-based systems with a contactless, accurate approach—detecting unauthorized entries or exits during class hours and instantly notifying faculty via a web dashboard. Built for smarter, safer, and more efficient campus management.

##🔧 Methodology (with Technologies)
  ###📂 Dataset Preparation
      🛠️ Tech Used: Python, OpenCV
      📸 Captured multiple face images per student using a webcam
      📁 Organized images into folders: "StudentName_RegistrationNumber"

  ###🧼 Preprocessing
      🛠️ Tech Used: OpenCV
      📏 Resized all images to 112×112 pixels
      🎨 Applied:
                Histogram Equalization
                Data Augmentation 

  ###🧠 Model Training
      🛠️ Tech Used: DeepFace, ArcFace
      📚 Used pre-trained ArcFace within DeepFace for facial embedding
      📊 Trained on the student dataset to improve recognition accuracy

  ###👁️ Face Detection
      🛠️ Tech Used: OpenCV, MTCNN
      🎥 Captured live video at the college gate
      🔍 Detected and aligned faces using MTCNN

  ###🧾 Face Recognition
      🛠️ Tech Used: DeepFace, Arc Face, Cosine Similarity
      🔍 Compared detected faces with stored embeddings
      ✅ Retrieved student info if matched
      ❌ Flagged as unauthorized if no match found

  ###🔄 Real-Time Monitoring
      🕵️‍♂️ Continuously monitored student movement
      🕒 Logged entry/exit time automatically in the database

  ###🌐 Web Dashboard
      🛠️ Tech Used: PHP, MySQL
      🖥️ Central platform for faculty and HOD interaction:
      👨‍🏫 Faculty Dashboard
              View and update student records
              Mark informed entries/exits
      👩‍💼 HOD Dashboard
              Receive real-time alerts
              Access detailed movement logs

  ###🚨 Alert System
      🛠️ Tech Used: Web Notification
      ⚠️ Automatically triggered for unauthorized entries/exits during class hours
      📩 Includes:
              👤 Student’s Name
              🏫 Department
              🆔 Roll Number
              🕒 Timestamp
              📤 Instantly sent to HOD dashboard for action
  
##🌱 Future Scope
   * Mobile Application Support:
      Develop a mobile app for faculty and HODs to receive real-time alerts and manage student records remotely.
   * Multi-Location Camera Integration:
      Extend the system to support multiple camera inputs for monitoring different campus gates or buildings.
   * Visitor and Staff Monitoring:
      Expand facial recognition to track staff and visitor movements for complete campus security coverage.
   * Parent Notification System:
      Enable automated SMS or email notifications to parents for repeated unauthorized student movements.
   * Advanced Analytics Dashboard
      Introduce visual reports and insights such as movement patterns, peak hours, and attendance trends.

##✅ Conclusion
  This mini project demonstrates the practical use of AI and facial recognition to build a secure and intelligent campus monitoring system. By automating student     tracking and delivering real-time alerts, the system improves safety, reduces manual workload, and increases administrative transparency. With future               enhancements, it holds the potential to become a scalable, institution-wide smart campus solution.This project greatly enhanced our technical and problem-solving   skills by giving us hands-on experience in AI, facial recognition, and real-time system development
  
