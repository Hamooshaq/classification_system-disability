Disability Classification System

This project aims to classify disabilities using TensorFlow and Convolutional Neural Networks (CNN), specifically focusing on distinguishing between different categories such as:

Human-Wheelchair
Wheelchair
Human
Features

CNN Model: Utilizes Convolutional Neural Networks for effective image classification.
Custom Dataset: Trained on images and annotations specific to the target classes.
User-Friendly Interface: Designed for easy deployment and usage.
Dataset Structure

The dataset is organized into the following structure:

bash
Copy code
dataset/
├── train/
│   ├── image/
│   └── annotation.csv
├── valid/
│   ├── image/
│   └── annotation.csv
└── test/
    ├── image/
    └── annotation.csv
Annotations
Each annotation.csv file contains:

filename: Name of the image file
label: Class of the disability (e.g., human-wheelchair, wheelchair, human)

Results

The classification model will output the predicted class along with confidence scores for each image. Example output:

Image:
Predicted Class: human-wheelchair

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

