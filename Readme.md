# Setup

This document provides instructions on how to set up and use the code repository organized in the following structure:

## Folder Structure
- **Codes**: Contains all the code scripts required for the project.
- **Dataset_Augmentation**: Holds scripts and data for dataset augmentation.
- **Encoder_Codes**: Includes the encoder-related code files and scripts.
- **Test Dataset**: Contains the test dataset files for model evaluation.
- **Trained Models**: Stores the trained model files.

---

## Setup Instructions

### 1. Clone the Repository
Download the Google Drive content locally and upload the content to a server or a local VSC machine after unzipping the file

### 2. Moving to the project 

cd ICPC

### 3. Set Up the virtual Environment

$ python -m venv venv

### 4. Installing Dependencies

$ source venv/bin/activate

$ pip install -r requirments.txt

### 5. Dataset_Augmentation

cd Dataset_Augmentation

The `README.md` contains detailed instructions on how to reproduce the results.

### 6. LoRA and DPO Training and Inference

cd Codes

The `README.md` contains detailed instructions on how to reproduce the results.

### 7. Encoder Models

- ### 7.1 GraphcodeBERT

  cd Encoder_Codes/GraphCodeBERT_codes
  
  The `README.md` contains detailed instructions on how to reproduce the results.

- ### 7.2 Unixcoder

  cd Encoder_Codes/UniXcoder_codes
  
  The `README.md` contains detailed instructions on how to reproduce the results.
