
# 🎥 Motion Detection using OpenCV

This project is a simple real-time motion detection system built using
Python and OpenCV. It captures video from your webcam and detects motion
by comparing consecutive frames, highlighting moving objects with
bounding boxes.

------------------------------------------------------------------------

## 🚀 Features

-   Real-time motion detection
-   Detects movement using frame differencing
-   Draws bounding boxes around moving objects
-   Lightweight and easy to understand
-   Works directly with your webcam

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python
-   OpenCV (cv2)

------------------------------------------------------------------------

## 📂 Project Structure

    ├── app.py   # Main motion detection script

------------------------------------------------------------------------

## ⚙️ How It Works

1.  Captures two consecutive frames from the webcam\
2.  Calculates the absolute difference between frames\
3.  Converts the result to grayscale\
4.  Applies Gaussian blur to reduce noise\
5.  Uses thresholding to highlight motion areas\
6.  Applies dilation to strengthen detected regions\
7.  Finds contours of moving objects\
8.  Draws rectangles around detected motion

------------------------------------------------------------------------

## 🧑‍💻 Installation

``` bash
pip install opencv-python
```

------------------------------------------------------------------------

## ▶️ Usage

``` bash
python app.py
```

------------------------------------------------------------------------

## ⌨️ Controls

-   Press **Q** → Quit the application

------------------------------------------------------------------------

## ⚠️ Requirements

-   Python 3.x
-   Webcam access
-   OpenCV installed

------------------------------------------------------------------------

## 🧠 Future Improvements

-   Add video recording for detected motion
-   Save motion clips automatically
-   Add alert system (email/notification)
-   Improve accuracy using AI/ML models
-   Integrate with smart surveillance systems

------------------------------------------------------------------------

## 📌 Author

**Vignesh Mani**
