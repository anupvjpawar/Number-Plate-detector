# Number-Plate-detector
# **Real-Time Number Plate Detection and Recognition**

This project demonstrates a **real-time number plate detection and recognition system** using **OpenCV**, **Haar Cascades**, and **Tesseract OCR**. The system captures video from a webcam, detects vehicle number plates, and recognizes the characters on the plate using **Optical Character Recognition (OCR)**.

## **Features**

- **Real-Time Detection:** Detects vehicle number plates in real-time using a webcam feed.
- **Haar Cascade Classifier:** Utilizes a pre-trained Haar Cascade classifier to detect number plates.
- **Optical Character Recognition (OCR):** Uses Tesseract OCR to extract and display the text from the detected number plates.
- **Visual Feedback:** Highlights detected number plates and displays the recognized text on the video feed.

## **Requirements**

- **Python 3.x**
- **OpenCV 4.x** (`opencv-python` package)
- **Tesseract-OCR** (`pytesseract` package)
- **Numpy** (`numpy` package)

## **Installation**

To set up this project, follow these steps:

### **Install Required Python Packages:**

Install the necessary Python packages using pip:

```bash
pip install opencv-python pytesseract numpy


Install Tesseract-OCR:
Windows: Download and install Tesseract from Tesseract-OCR GitHub.

Linux: Install Tesseract using your package manager:

bash
Copy code
sudo apt-get install tesseract-ocr
Ensure that Tesseract is correctly installed and added to your system's PATH.

Download Haar Cascade Classifier:
Download the haarcascade_russian_plate_number.xml file from the OpenCV GitHub repository and place it in the haarcascades/ directory.

Usage
Run the Number Plate Detection System:
Execute the Python script to start the real-time number plate detection and recognition:

bash
Copy code
python number_plate_detection.py
Quit the Application:
Press q on the keyboard to exit the application and close the video feed.

How It Works
Video Capture: Captures video from the default webcam.
Plate Detection: Detects number plates in the video stream using a Haar Cascade classifier.
OCR Processing: Extracts text from the detected number plates using Tesseract OCR.
Display Results: The video feed shows detected number plates and recognized text in real-time.
File Descriptions
number_plate_detection.py: The main Python script that runs the real-time number plate detection and OCR using OpenCV and Tesseract.
haarcascade_russian_plate_number.xml: Pre-trained Haar Cascade model for detecting number plates. (Download from the OpenCV GitHub repository).
