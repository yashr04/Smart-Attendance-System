# Smart Attendance System using Face Recognition

This **Smart Attendance System** is a Python-based solution that automates attendance recording through face recognition technology. Leveraging **OpenCV**, **Flask**, and a **Face Recognition Model**, this system captures and records attendance in real-time, ensuring accuracy, speed, and a user-friendly experience. It supports storage of attendance data in CSV files, making it easy to access and manage records.

## 🚀 Features

* **Face Recognition Technology**: Automatically detects and recognizes faces using the Haar cascade classifier and pre-trained models.
* **Real-Time Attendance Tracking**: Records attendance in real-time and logs data with timestamps.
* **User-Friendly Interface**: Clean, intuitive web-based interface designed with HTML for easy interaction.
* **CSV-Based Record Keeping**: Attendance data is saved in CSV files, simplifying data access and management.

## 🛠️ Technologies Used

* **Backend**: Python, Flask
* **Frontend**: HTML, CSS
* **Face Detection & Recognition**: OpenCV, Haar cascades, face recognition model
* **Data Storage**: CSV files for attendance logs
* **Version Control**: Git

## 📂 Folder Structure

```
.
├── Attendance System using Face Recognition
│   ├── .git
│   ├── Attendance
│   │   └── Attendance-02_15_23.csv
│   │   └── Attendance-10_20_23.csv
│   ├── static
│   │   └── faces
│   │   └── face_recognition_model.pkl
│   │   └── haarcascade_frontalface_default.xml
│   ├── templates
│   │   └── home.html
│   ├── app.py
│   └── ss.png
```

## 💡 How It Works

1. **User Interface**: A web interface allows users to start the system and view attendance logs.
2. **Face Recognition**: The system captures the user's face and compares it with the pre-trained face recognition model to mark attendance.
3. **Data Logging**: Once the face is recognized, attendance is recorded and stored in a timestamped CSV file.
4. **Attendance Records**: Users can retrieve attendance data from the CSV files in the /Attendance folder.

## 🖥️ Getting Started

### Prerequisites

- Python 3.x
- Flask
- OpenCV

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yashr04/smart-attendance-system.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```
