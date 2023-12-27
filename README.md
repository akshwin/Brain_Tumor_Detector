# Brain Tumor Detection Project

## Overview
Welcome to the Brain Tumor Detection Project! This project utilizes deep learning techniques to analyze MRI images and detect the presence of brain tumors. The system is equipped with an intuitive user interface developed using Streamlit, allowing users to upload their MRI images for real-time tumor detection.

## Project Steps

### 1. Data Exploration
- Explored the Kaggle Brain Tumor MRI Dataset to understand the structure and content of the data.
- Identified the categories for classification: Glioma, Meningioma, Pituitary, and No Tumor.

### 2. Model Training
- Developed a convolutional neural network (CNN) based on the VGG16 architecture for image classification.
- Utilized transfer learning with pre-trained weights from the ImageNet dataset.
- Configured the model for binary classification (Tumor vs. No Tumor) by adapting the last layer.

### 3. Data Preprocessing
- Employed the Keras ImageDataGenerator for real-time data augmentation during model training.
- Normalized pixel values to the range [0, 1] to enhance model convergence.

### 4. Model Evaluation
- Split the dataset into training and testing sets.
- Trained the model on the training set and evaluated its performance on the testing set.
- Monitored key metrics such as accuracy, loss, validation accuracy, and validation loss.

### 5. Model Saving and Deployment
- Saved the trained model as an HDF5 file (`model_vgg16.h5`) for future use.
- Explored the potential for deployment, considering options like web applications or cloud platforms.

### 6. Streamlit Web Application
- Developed a Streamlit-powered web application (`streamlit_app.py`) to provide a user-friendly interface for tumor detection.
- Integrated the trained model into the application for real-time predictions.
- Implemented features for uploading MRI images and displaying the detection results.

### 7. User Interface Testing
- Conducted testing using demo MRI images to ensure the proper functioning of the web application.
- Obtained user feedback and iteratively improved the interface for a seamless experience.

### 8. Documentation and Readme
- Created comprehensive documentation, including a readme file, to guide users on running the project and understanding its components.
- Shared information on the project structure, code files, and potential areas for future enhancements.

## How to Run
1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed (e.g., TensorFlow, Keras, Streamlit).
3. Run the Streamlit app using the following command:
   ```
   streamlit run streamlit_app.py
   ```
4. Access the web application in your browser and upload an MRI image for tumor detection from the link below
    ```
    https://brain-tumors-detector.streamlit.app/
   ```

Feel free to explore, contribute, and provide feedback to help improve the Brain Tumor Detection Project. Together, we can make a positive impact on healthcare technology! 🌐🧠✨
