🧠 Object Detection using YOLOv5 (Person Detection)
📌 Project Overview

This project implements real-time object detection using the YOLOv5 (You Only Look Once) deep learning model.
The primary focus of this project is person detection, but since YOLOv5 is a general object detection model, it is also capable of detecting other objects such as buses, umbrellas, etc.

The model identifies objects in images and draws bounding boxes with class labels and confidence scores.

🎯 Objectives

To understand and implement YOLOv5 for object detection

To detect persons in images using a pre-trained YOLOv5 model

To visualize detection results with bounding boxes and confidence values

To gain hands-on experience with deep learning and computer vision

🛠️ Technologies Used

Python

YOLOv5

PyTorch

OpenCV

Jupyter Notebook

NumPy

Matplotlib

📂 Project Structure
├── Face_Detection_YOLOv5.ipynb
├── yolov5/
│   ├── models/
│   ├── utils/
│   ├── weights/
├── sample_images/
├── outputs/
└── README.md

🚀 How It Works

Load the YOLOv5 pre-trained weights

Provide an input image

The model processes the image

Detected objects are displayed with:

Bounding boxes

Class labels (e.g., person, bus)

Confidence scores

📸 Sample Output

Persons detected with bounding boxes labeled as person

Other objects (e.g., bus) may also appear based on the model’s predictions

Confidence values indicate the probability of correct detection

Note: The colored bounding boxes and confidence scores shown in the output are expected results of YOLOv5 inference and do not indicate any error.

⚠️ Important Note

Although this project is referred to as Person Detection, it is technically an Object Detection Project, since YOLOv5 detects multiple object classes by default.
Person detection is achieved by focusing on the person class from the detected outputs.

✅ Results

Successfully detected multiple persons in a single image

Achieved high confidence scores for detected objects

Demonstrated effective use of YOLOv5 for real-world scenarios

🔮 Future Enhancements

Restrict detection only to the person class

Extend to real-time webcam detection

Improve accuracy using custom-trained datasets

Deploy as a web or mobile application
