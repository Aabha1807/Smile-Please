# Smile-Please
A Real-Time Facial Expression Classification Using Convolution Neural Network

## Project Description
"Smile Detection" is a real-time facial expression classification project that uses Convolutional Neural Networks (CNNs) to identify whether a person is smiling. The project leverages deep learning techniques to analyze images of faces and accurately classify them based on the presence of a smile.

## Data Sources
The model is trained on the `FER2013` dataset, which has been modified to categorize expressions into two classes:
- **Happy**: Images where individuals are smiling.
- **Not Happy**: Consists of images that represent sadness, surprise, and anger.

These datasets include diverse facial images which help the model learn and generalize well across different facial features and expressions.

## Requirements
To run this notebook, you will need the following packages:
- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- Tensorflow Model Optimization
- A Raspberry Pi with a connected camera module

Install these packages using pip:
```bash
pip install tensorflow numpy matplotlib opencv-python
```
## Deployment on Raspberry Pi

This model is deployed on a Raspberry Pi, which uses a connected camera to capture video in real-time. The system continuously analyzes the video feed, and once it detects a 'Happy' expression (smile), it triggers a specific action. 

## Setup Instructions
Set up your Raspberry Pi with the latest version of Raspberry Pi OS.
Connect the camera module to the Raspberry Pi.
Ensure all dependencies are installed.
Run the code for testing real time classification `ImageApplyModel.ipynb` notebook.

## Running the Notebook
To run the `SmileDetection.ipynb` notebook:
1. Ensure you have Jupyter Notebook installed, or use Google Colab.
2. Open the notebook in Jupyter or Colab.
3. Run the cells sequentially to see the model in action.

## Outputs
The notebook will display the processed images with predictions indicating whether the person in the image is smiling.

## Acknowledgments
This project was inspired by the need for automated real-time facial expression recognition in various applications.
