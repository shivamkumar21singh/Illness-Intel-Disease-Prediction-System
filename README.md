# Illness-Intel-Disease-Prediction-System

**Overview**

Illness Intel is an intelligent disease prediction system designed to assist users in identifying potential illnesses based on their symptoms. Leveraging the power of machine learning, the system provides an accurate prediction of diseases and suggests precautions to prevent or mitigate them.

**Features**

1) Symptom-Based Disease Prediction: Users can input symptoms to get predictions for possible diseases.
2) Disease Description: Provides detailed information about the predicted disease.
3) Precautionary Measures: Suggests actionable steps to prevent or reduce the severity of the disease.
4) User-Friendly Interface: Built with Gradio for easy interaction.

**How It Works**

1) Users input symptoms via an intuitive interface.
2) The system analyzes the inputs using a trained Random Forest model.
3) Predictions are displayed along with disease descriptions and precautionary measures.

**Dataset**

The system uses multiple datasets to achieve its objectives:

1) Symptom-Disease Dataset: Contains symptoms for each disease.
2) Disease Descriptions Dataset: Provides a brief description of each disease.
3) Symptom Severity Dataset: Assigns a weight to symptoms based on severity.
4) Precautionary Measures Dataset: Lists preventive measures for diseases.

**Technology Stack**

Python: Core programming language.
Machine Learning: Random Forest model for prediction.
Gradio: Used for building the user interface.
Deployment: Deployed on Hugging Face Spaces.

**Deployment**

The project is deployed on Hugging Face Spaces and can be accessed https://huggingface.co/spaces/anubhaha/Illness_Intel_Disease_Prediction_System.

**Usage**

1) Input your symptoms into the text field or dropdown options.
2) Click on the "Predict" button to get results.
3) View the predicted disease, its description, and precautions.
