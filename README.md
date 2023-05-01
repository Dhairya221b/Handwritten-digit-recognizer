# Handwritten Digit Recognition using Image Processing

This project is an implementation of a handwritten digit recognition system using image processing techniques. The system is designed to recognize digits from 0 to 9 that are handwritten on a piece of paper or any other image source.

## Requirements
- Python 3
- Tensorflow
- Keras 
- Numpy
- tkinter
- win32gui

## How to Use
1. Clone this repository to your local machine.
2. Install the required packages listed in the requirements section.
3. Run the `Text_Recognision.py`.
4. Select an image with a handwritten digit on it.
5. The system will process the image and display the recognized digit.

## How it Works
The system works by processing the input image in several steps:
1. Preprocessing: The input image is converted to grayscale and smoothed using a Gaussian filter.
2. Thresholding: A binary image is created from the preprocessed image by applying a threshold value.
3. Contour Detection: The contours of the objects in the binary image are detected and extracted.
4. Digit Extraction: The contours are filtered to extract only the digit.
5. Feature Extraction: A set of features are extracted from the digit, such as area, perimeter, and aspect ratio.
6. Classification: The features are fed into a machine learning model to classify the digit.

## Future Improvements
- Improve the accuracy of the digit recognition system by experimenting with different machine learning models and feature extraction techniques.
- Add support for recognizing digits in real-time using a webcam or a smartphone camera.
- Implement a user interface for a more user-friendly experience.


### Model File
https://drive.google.com/file/d/1zEt-ncGuLHL_fI-gNg3Iy4hBRh00guFH/view?usp=share_link

## Credit 
This project created by Dhiarya Satani for AI subject in Marwadi University.
