# Car Object Detection with YOLO

This repository contains code for a self-driving car object detection system using the YOLO (You Only Look Once) algorithm. The system can detect various objects, including cars, in images and video streams from a mounted camera on the car's hood.

## Model Overview

The YOLO algorithm is a real-time object detection system that "only looks once" at the image to make predictions. It uses a deep convolutional neural network to detect objects and their bounding boxes in an input image. The model output consists of bounding boxes and class probabilities for each object detected.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies:
   - TensorFlow (v2.0 or higher)
   - NumPy
   - OpenCV

   You can install the dependencies using pip: pip install tensorflow numpy opencv-python

3. Download the pre-trained YOLO weights from the link provided in the notebooks.

## Usage

To use the self-driving car object detection system, follow the instructions in the Jupyter notebook provided in the `notebooks` directory. The notebook guides you through the steps of loading the pre-trained YOLO model, performing object detection on test images, and visualizing the results.

## Results

The YOLO algorithm achieves high accuracy in object detection and can run in real-time. The results of object detection on test images and videos demonstrate the effectiveness of the model in identifying cars and other objects.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



