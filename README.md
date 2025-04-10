Deepfake Image Detection Android App
This project is an Android application that enables users to detect deepfake images using a machine learning model. It is designed to provide an accessible and reliable tool for identifying manipulated facial images, contributing to digital safety and content authenticity.

Overview
The application leverages the XceptionNet architecture, converted to TensorFlow Lite format for mobile compatibility. The model processes user-uploaded images and returns a classification indicating whether the image is real or fake. This tool is particularly useful for social media verification, digital forensics, and research purposes.

Features
Deepfake detection powered by XceptionNet

Image upload via camera or gallery

On-device inference using TensorFlow Lite for privacy

Real-time classification of input images

Modular structure for easy updates and model replacements

Firebase integration (optional) for remote model storage and updates

Technology Stack
Android Studio (Java/Kotlin)

TensorFlow Lite

XceptionNet (pre-trained)

OpenCV (for image processing, optional)


Use Cases
This application serves individuals and organizations interested in verifying the authenticity of images. It is relevant in the fields of journalism, education, digital forensics, and social media monitoring.

Installation
Clone the repository

Open the project in Android Studio

Ensure TensorFlow Lite model is placed in the assets folder

Build and run the app on an Android device

Contribution
Contributions are welcome. Please fork the repository and create a pull request with a clear description of the changes made. You can also open issues for bugs or feature requests.
