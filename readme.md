# Ceramic Tiles Quality Inspection

This repository contains the implementation of a defect detection system for ceramic tiles using YOLOv5, OpenCV, and the Flask library in Python for backend development. The frontend is developed using HTML and CSS.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Adding Images](#adding-images)
- [Contributing](#contributing)

## Introduction

This project aims to detect defects in ceramic tiles using deep learning and computer vision techniques. YOLOv5 is used for defect detection, while the backend is built with Flask in Python. The frontend uses HTML and CSS to provide a user-friendly interface. OpenCV is used for additional image processing tasks.

## Features

- Upload images of ceramic tiles for defect analysis.
- Real-time defect detection using YOLOv5.
- Defect highlighting and detailed analysis.
- User-friendly web interface.
- Detailed defect reports.

![CTQS-GoogleChrome2024-07-1304-23-20online-video-cutter com-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/9207d24e-62db-442f-ba05-34e79ff9957e)

## Technologies Used

- **Backend:** Flask, Python
- **Frontend:** HTML, CSS
- **Image Processing:** OpenCV
- **Deep Learning:** YOLOv5

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/Adeen317/CTQI-Flask.git
    cd CTQI-Flask
    ```

2. **Create a virtual environment and activate it:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Download YOLOv5 weights:**

    Download the pre-trained YOLOv5 model weights and place them in the `weights` directory.

## Usage

1. **Run the Flask application:**

    ```sh
    python main.py
    ```

2. **Open your web browser and navigate to:**

    ```
    http://127.0.0.1:5000
    ```

3. **Upload an image of a ceramic tile and click on 'Analyze' to detect defects.**

## Project Structure

```
ceramic-tiles-defect-detection/
│
├── app.py                # Main Flask application
├── templates/
│   └── index.html        # HTML file for the frontend
├── static/
│   ├── css/
│   │   └── styles.css    # CSS file for styling
│   └── images/           # Folder for sample images
├── defect_detection/
│   ├── detect.py         # Python script for defect detection using OpenCV
│   └── yolov5.py         # Python script for YOLOv5 defect detection
├── weights/
│   └── yolov5s.pt        # YOLOv5 model weights
├── requirements.txt      # List of required packages
└── README.md             # Project documentation
```


## Contributing

Contributions are welcome! Please create a pull request with a detailed description of your changes.
