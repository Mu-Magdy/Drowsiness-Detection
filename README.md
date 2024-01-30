## Drowsiness Detection using YOLO

### Overview:
Drowsiness Detection using YOLO is a computer vision project aimed at detecting drowsiness in individuals using the YOLO (You Only Look Once) object detection framework. The project utilizes a pre-trained YOLO model to detect faces and eyes in real-time from video streams or webcam feeds. By analyzing the state of the eyes, the system can determine if a person is drowsy or not.

### Requirements:
- Python 3.x
- OpenCV
- YOLOv5 (pre-trained weights and configuration files)
- NumPy

### Installation:
1. Install Python 3.x from the official website or using a package manager.
2. Create virtual environment 
   ```
   python -m venv {any name}
   ```
   Activate the environment: [link](https://docs.python.org/3/library/venv.html#:~:text=A%20virtual%20environment%20may,containing%20the%20virtual%20environment)

2. Install OpenCV using pip:
   ```
   pip install opencv-python
   ```
3. Clone or download the YOLOv5 repository containing the pre-trained weights and configuration files and install requirements.
    ```
    git clone https://github.com/ultralytics/yolov5
    cd yolov5 & pip install -r requirements.txt
    ```
4. Install NumPy using pip:
   ```
   pip install numpy
   ```
5. Clone labelImg annotator
    ```
    git clone https://github.com/tzutalin/labelImg

    ```
    And isntall its requirements
    ```
    pip install pyqt5 lxml --upgrade
    cd labelImg && pyrcc5 -o libs/resources.py resources.qrc
    ```

### Usage:
1. Clone or download the Drowsiness Detection project repository.
2. Navigate to the project directory.
4. Collect your data set and label your images using openCV and labelimg
5. The application will launch a webcam feed or video stream, and it will detect drowsiness in real-time by analyzing the eyes of individuals.

### Project Structure:
- `drowsiness_detection.py`: Main Python script for running the drowsiness detection application.
- `README.md`: Readme file containing project information and instructions.

### Credits:
- This project is based on the YOLO object detection framework.
- YOLOv5 implementations are available from the official repositories.
- The project utilizes OpenCV for real-time video processing and analysis.

### Disclaimer:
This project is intended for educational purposes only. It should not be used in situations where the accuracy or reliability of the drowsiness detection is critical for safety or security purposes. Always use caution and ensure the proper functioning of the system in real-world scenarios.