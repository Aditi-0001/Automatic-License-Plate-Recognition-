# Automatic-License-Plate-Recognition 
A real-time Automatic License Plate Recognition (ALPR) system using OpenCV, EasyOCR, and Flask. Captures number plates from a webcam feed, extracts text, and displays results via a web interface.
## Setup Instructions :

### 1. Clone the repository
### 2. Create virtual environment (optional but recommended)
   
### 3. Install dependencies
- All the necessary libraries are included in the requirements.txt file . Install them by running the command - 
  
   pip install -r requirements.txt
  
### 4. Run the application

- app.py

- Visit http://127.0.0.1:5000 in your browser.

### 5. Configuration Notes

- Default webcam is used for video feed. Modify cv2.VideoCapture(0) if needed.
  
- Place a car image with a visible number plate in front of the camera, then click the 'Capture & Detect' button to display the detected number.

- Captured plate images are saved in the plates/ directory.

## Screenshots :

![Screenshot 2025-04-30 001502](https://github.com/user-attachments/assets/0bc5ae3d-541b-4152-af99-d2bdb74bd503)

![Screenshot 2025-04-30 003150](https://github.com/user-attachments/assets/06ebe6ee-65fa-4b72-841a-688b3298a79a)


