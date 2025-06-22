# EyeSight
Integrative AI for Non-Invasive Diabetic Retinopathy Detection Using Pupillometry and Ensemble Deep Learning

## What the Project Does

This project presents **EyeSight**, a non-invasive, AI-powered diagnostic system for early detection and classification of **Diabetic Retinopathy (DR)**. By using **pupillometry**—analyzing the eye's pupil response to light—combined with ensemble deep learning models (EfficientNetB3, DenseNet169, and ResNet50), the system accurately predicts the stage of DR. A **Streamlit-based web interface** enables clinicians to interact with the model in real-time for swift and accessible diagnosis.

## Why the Project is Useful

Diabetic Retinopathy is a leading cause of vision loss globally, particularly among diabetic patients. Traditional diagnostic methods require expensive retinal imaging equipment, which limits accessibility in rural and resource-constrained areas. EyeSight offers a **low-cost, real-time screening alternative** by analyzing readily accessible pupillometry data.

- Enables early intervention and monitoring.
- Reduces reliance on costly fundus cameras.
- Helps healthcare professionals make informed decisions quickly.
- Designed for low-resource clinical settings, enhancing rural accessibility.

## How Users Can Get Started with the Project

### Prerequisites

Ensure you have Python installed, along with the following packages:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- streamlit
- OpenCV

### Dataset

Ensure the pupillometry dataset is present in the working directory.

## Running the Project

1. Clone this repository.
2. Open and run the notebook: `Diabetic_retinopathy_detection.ipynb` to:
   - Train models using pupillometry features.
   - Evaluate performance (Accuracy, Precision, Confusion Matrix, etc.).
   - Export the best-performing model (EfficientNetB3).
3. Launch the Streamlit web app:
   ```bash
   streamlit run .\app.py
   ```
4. Use the GUI to upload pupil images and predict DR stages.

## Usage

The system classifies the user input into one of five DR stages (0–4). The user needs to input key pupillometry readings, and the model will output:

- Predicted DR Stage  
- Preventive & Precautionary Measures  

