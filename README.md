# Face Recognition Based Attendance System

An intelligent and efficient attendance management system leveraging face recognition technology. This project eliminates the need for manual attendance tracking, offering a seamless and automated process.

## Features

1. Real-time face detection and recognition using advanced machine learning algorithms.
2. User-friendly interface for administrators to view and manage attendance records.
3. Secure and scalable solution adaptable for institutions, workplaces, and events.
4. Integration with databases for storing and retrieving attendance data.

## Technologies Used

1. Python (OpenCV, NumPy, face_recognition library)
2. Machine Learning models for face detection and recognition.
3. Database integration (e.g., SQLite/MySQL).
4. Optional: Flask/Django for a web-based interface.

## Installation

1. Clone the repository to your local machine. ``` git clone  ```
2. Install the required packages using ```pip install -r requirements.txt```.
3. Download the dlib models from https://drive.google.com/drive/folders/12It2jeNQOxwStBxtagL1vvIJokoz-DL4?usp=sharing and place the data folder inside the repo

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.

## Future Enhancements

1. Adding mobile app integration.
2. Enhancing accuracy with deep learning models.
3. Cloud deployment for remote access


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have any suggestions.





