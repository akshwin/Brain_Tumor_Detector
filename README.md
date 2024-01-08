
# Brain Tumor Detection using Deep Learning 
---


## Overview

This project is a web application that utilizes Streamlit, TensorFlow, and Keras for detecting brain tumors in MRI images. The application allows users to upload an MRI image, and it provides predictions on whether a tumor is present and, if so, the type of tumor detected.

## Installation

1. **Clone the repository:**
   - Clone the project repository to your local machine.

2. **Install the required dependencies:**
   - Install the necessary dependencies by running the command: `pip install -r requirements.txt`.

## Usage

1. **Run the application:**
   - Start the application by running the command: `streamlit run brain_tumor_detection.py`.

2. **Access the application:**
   - Open your web browser and navigate to [http://localhost:8501](http://localhost:8501).

3. **Upload an MRI image:**
   - Utilize the provided file uploader to select and upload an MRI image.

4. **View prediction results:**
   - The application will display the uploaded image along with predictions regarding the presence and type of brain tumor.

## Model

- The brain tumor detection model is included in the `brain_tumor.h5` file. Ensure that this file is available in the project directory.

## File Structure

- **`brain_tumor_detection.py`:**
  - This script contains the main logic for the Streamlit application.

- **`requirements.txt`:**
  - This file lists the dependencies required to run the application. Install them using `pip install -r requirements.txt`.

- **`brain_tumor.h5`:**
  - This file contains the pre-trained brain tumor detection model.

## Troubleshooting

- **Model Loading Issues:**
  - If there are issues loading the model, ensure that the `brain_tumor.h5` file is present, and the required dependencies are installed.

## To run the applicton live online , click the below link 
https://brain-tumor-detectors.streamlit.app/
