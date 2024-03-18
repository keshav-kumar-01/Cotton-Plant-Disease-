
# Cotton Disease Detection using ResNet152V2

This project utilizes the ResNet152V2 architecture for detecting diseases in cotton plants. The model is trained using a dataset containing images of healthy and diseased cotton plants. The implementation is done using TensorFlow 2.9.1.

## Installation

To run the code, you need to install TensorFlow version 2.9.1. You can install it using pip:

```bash
!pip install tensorflow==2.9.1
```

## Usage

1. Clone the repository:

```bash
git clone <https://github.com/keshav-kumar-01/Cotton-Plant-Disease-.git>
```

2. Install the required dependencies:

```bash
# Assuming you are using a virtual environment
pip install -r requirements.txt
```

3. Run the provided Python script:

```bash
python cotton_disease_detection.py
```

## Steps in the Notebook

1. Importing Libraries and Setting Up Environment
2. Mounting Google Drive
3. Downloading Dataset
4. Preprocessing and Configuring GPU Options
5. Loading Pre-trained ResNet152V2 Model
6. Freezing Layers in the Base Model
7. Adding Fully Connected Layers
8. Compiling the Model
9. Training the Model
10. Plotting Training Metrics (Loss and Accuracy)
11. Evaluating the Model Using Confusion Matrix
12. Saving the Model
13. Predicting New Images Using the Saved Model
```

Feel free to modify the installation and usage instructions based on your specific setup and preferences.
