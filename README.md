# Object Detection with YOLO

This Python script performs object detection using the YOLO (You Only Look Once) algorithm. It detects objects in an input image and annotates them with bounding boxes and class labels.

## Features

- Loads pre-trained YOLO model weights and configuration files (`yolov3.weights` and `yolov3.cfg`).
- Utilizes the COCO dataset class names from the `coco.names` file for object detection.
- Reads an input image from the file system.
- Prepares the image for input to the YOLO network by resizing and normalization.
- Performs a forward pass through the YOLO network to obtain detection results.
- Processes the detection results and annotates the image with bounding boxes and class labels for detected objects.
- Displays the annotated image using Matplotlib.
- Prints the detected objects along with their class labels and confidence scores.

## Requirements

- Python 3.x
- OpenCV (cv2)
- Matplotlib

## Usage

1. Clone this repository.
2. Place the YOLO model files (`yolov3.weights`, `yolov3.cfg`) and the `coco.names` file in the same directory as the script.
3. Specify the path to the input image in the script (`sample_image.jpg`).
4. Run the script and view the detected objects in the output image.

Feel free to modify the script or experiment with different images and model configurations to explore object detection further!
