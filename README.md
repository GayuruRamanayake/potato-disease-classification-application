# Potato Disease Detection Model Training

This repository contains the code and instructions for training a potato disease detection model. Follow the steps below to set up your environment, install necessary packages, and train the model.

## Prerequisites

Before getting started, ensure you have the following installed:

- **Python 3.x**: You can download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
  
  Make sure Python is added to your system's PATH.

- **pip**: Python's package installer. It is typically included with Python 3.x installations.

## Setting Up Python Environment

1. **Install Python Packages**:
   
   Navigate to the project directory and install the required Python packages for both the `training` and `api` sections.

   ```bash
   pip3 install -r training/requirements.txt
   pip3 install -r api/requirements.txt


# Potato Disease Detection Model

This project involves training a machine learning model for detecting diseases in potatoes using image classification. Follow the instructions below to set up the environment, train the model, and prepare for deployment using TensorFlow Serving.

## Model Training

### 1. Download the Data
- Download the dataset from [Kaggle](https://www.kaggle.com/).
- Ensure that you keep only the folders related to potato diseases.

### 2. Run Jupyter Notebook
- Open a terminal in your project directory and run the following command to launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
- This will open Jupyter Notebook in your browser.

### 3. Open the Training Notebook
- In Jupyter, navigate to the `training` folder and open the `potato-disease-training.ipynb` file.

### 4. Update the Dataset Path
- Locate **Cell #2** in the notebook and update the path to point to your dataset.

### 5. Run the Notebook
- Run all cells in the notebook one by one to train the model.

### 6. Save the Trained Model
- Once the training is complete, save the generated model in the `models` folder. Name it appropriately (e.g., `model_v1.h5`).

## TensorFlow Serving Setup

Install TensorFlow Serving for deploying the trained model. Refer to the official [TensorFlow Serving Installation Guide](https://www.tensorflow.org/tfx/guide/serving) for detailed instructions.

## Additional Notes
- Ensure you have the required dataset files before starting the training process.
- You can adjust parameters and configurations in the Jupyter Notebook to improve model performance based on your needs.

## Dependencies

- Python 3.x
- TensorFlow
- Jupyter Notebook

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
