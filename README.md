# Pedestrian_Bounding_Box


# Pedestrian Detection and Counting System
A web-based application designed to detect and count pedestrians in real-time using a trained YOLOv8 model. This system allows users to upload images, applies bounding boxes to detected pedestrians, and displays the results dynamically.

## Overview
- **Model Training**: The YOLOv8 model was trained on a custom pedestrian dataset to achieve accurate bounding box detection.
- **Performance Metrics**: The model achieved 96.5% accuracy, 95.2% precision, 94.8% recall, and 95.0% F1-score on validation data.
- **Web Application**: Developed using Flask for user-friendly image uploads and real-time pedestrian detection.
- **Image Processing**: Utilizes OpenCV for image processing and bounding box visualization.
- **Deployment**: Dockerized and deployed to an AWS EC2 instance for scalability and accessibility.

## Technologies Used
- **Programming Language**: Python
- **Deep Learning Framework**: PyTorch
- **Object Detection Model**: YOLOv8
- **Image Processing Library**: OpenCV
- **Web Framework**: Flask
- **Containerization**: Docker
- **Cloud Platform**: AWS EC2
- **Frontend**: HTML/CSS
