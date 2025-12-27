# Face Recognition System

## Project Overview
This project is a **Face Recognition System** developed using **Python and OpenCV**.  
The system detects human faces from a webcam and recognizes trained users in real time using computer vision techniques.

## Technologies Used
- Python  
- OpenCV  
- NumPy  
- Jupyter Notebook  
- Haar Cascade Classifier  
- LBPH (Local Binary Pattern Histogram) Algorithm  

## How the System Works
1. Captures face images using a webcam.
2. Stores face images in a dataset for training.
3. Converts images to grayscale for preprocessing.
4. Uses Haar Cascade to detect faces.
5. Trains the model using the LBPH algorithm.
6. Recognizes trained faces in real time through webcam input.

## Project Structure
Face-Recognition-System/
├── Face_Recognition_Project.ipynb
├── dataset/
├── trainer/

yaml

## How to Run the Project
1. Clone or download the repository.
2. Open **Jupyter Notebook**.
3. Open `Face_Recognition_Project.ipynb`.
4. Install required libraries:
pip install opencv-python opencv-contrib-python numpy

yaml

5. Run the notebook cells step by step.

## Features
- Real-time face detection
- Face recognition using LBPH algorithm
- Handles known and unknown faces
- Simple and beginner-friendly implementation

## Use Case
This project can be used as:
- An academic mini-project
- A beginner computer vision project
- A resume project for AIML / Software internships

## Note
- The dataset contains personal face images and is not recommended for public sharing.
- The trained model file is generated after training.

## Author
Developed by a B.Tech AIML student as part of learning computer vision using Python.
