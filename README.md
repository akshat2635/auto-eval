
# Auto Evaluation System for True/False Answer Sheets NCVPRIPG24

# Team Name - AI Avengers
- One of the top-5 teams in the NCVPRIPG'24 Summer Challenge.

# Members - <br />
- Akshat Jain (B22CS007)<br />
- Gaurav Manish (B22CS079)<br />
- Mukund Gupta (B22CS086)<br />
- Rutam Rajhansa (B22ME055)<br />

## Overview

This project involves an automated evaluation system designed to grade true/false answer sheets from images. The system ensures the correct orientation of the answer sheets, filters out unwanted text, and extracts the answers using OCR (Optical Character Recognition) technologies.

## Features

- **Automated Image Orientation Correction**: Utilizes PyTesseract to correct the orientation of the input images.
- **Image Processing**: Applies Gaussian blur to focus on the answer areas and filter out unwanted text.
- **Optical Character Recognition**: Uses EasyOCR to accurately read and extract answers from the processed images.
- **Validation and Error Handling**: Implements comprehensive checks to ensure the accuracy and reliability of the system.

## Technologies Used

- **Python**: Primary programming language.
- **PyTesseract**: For OCR-based image orientation correction.
- **OpenCV**: For image processing tasks, including applying Gaussian blur.
- **EasyOCR**: For extracting text from images.
- **NumPy**: For numerical operations and array handling.
- **Matplotlib**: For visualizing and debugging image processing steps.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/auto-evaluation-system.git
   cd auto-evaluation-system

