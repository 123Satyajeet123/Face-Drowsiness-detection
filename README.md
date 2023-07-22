# Face Drowsiness Detection System using YOLOv5

<p align="center">
  <img src="https://github.com/123Satyajeet123/Face-Drowsiness-detection/assets/103361055/15dfd9dc-752c-4a3d-8bec-c991e558c49e" alt="logos" heigth=200rem>
</p>

This repository contains a system that uses YOLOv5 to detect faces and determines whether the person is awake or drowsy. The project includes the necessary code to set up the YOLOv5 environment and perform face detection.

## Description

The Face Drowsiness Detection System uses YOLOv5, a popular object detection model, to detect faces in images. After detecting the face, the system then applies a drowsiness detection algorithm to determine if the person in the image is awake or drowsy.

## Prerequisites

To run this project, you need the following dependencies:

- Python 3.x
- OpenCV (cv2)
- Torch
- Matplotlib
- NumPy
- TensorFlow (tf)
- YOLOv5

You can install the required packages using `pip`:

```bash
pip install opencv-python torch matplotlib numpy tensorflow
```

## How to Use
1. Clone the YOLOv5 Repository
Follow these steps to set up and use the Face Drowsiness Detection System:
```
git clone https://github.com/ultralytics/yolov5
cd yolov5
```
2. Install YOLOv5 Requirements
```
pip install -qr requirements.txt
```

3. Upload the Zip File
Upload the zip file containing your face images to the Colab environment.

4. Extract the Zip File
Extract the contents of the uploaded zip file to the "datasets" folder within the YOLOv5 directory.

5. Run the Face Drowsiness Detection
Run the following command to start the face drowsiness detection process:
```
python train.py --img 640 --batch 16 --epochs 500 --data myface.yaml --weights yolov5m.pt --cache
```

The system will use YOLOv5 to detect faces in the provided images and determine whether the person is awake or drowsy.

## Dataset and Model
The system utilizes a custom dataset of face images, which you need to provide in the uploaded zip file. It uses the YOLOv5m model architecture for face detection.

## Performance
The accuracy of the drowsiness detection system depends on the quality and diversity of the provided face images. Ensure that the images contain clear and representative samples of both awake and drowsy faces for better results.

## License
This project is licensed under the "Fck it, I don't care"








