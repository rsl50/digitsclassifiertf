# Digit Classifier with TensorFlow Lite

This project is an Android application that demonstrates how to use TensorFlow Lite to classify handwritten digits. It's based on the concepts and techniques introduced in the official Android codelab: [Classify digits with TensorFlow Lite](https://developer.android.com/codelabs/digit-classifier-tflite).

## Overview

The application allows users to draw a digit on the screen, and then it uses a pre-trained TensorFlow Lite model to predict the digit. The model is trained to recognize digits from 0 to 9.

## Features

*   **Handwritten Digit Recognition:** Users can draw digits on the screen.
*   **TensorFlow Lite Integration:** The app uses a TensorFlow Lite model for efficient on-device inference.
*   **Real-time Prediction:** The app provides real-time feedback on the predicted digit.
*   **Clear Canvas:** A button to clear the canvas and start over.
* **Kotlin:** The project is written in Kotlin.
* **Modern Android Development:** The project uses modern Android development practices.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Android Studio (latest stable version recommended)
*   Android SDK (API level 21 or higher)
*   A physical Android device or an emulator

### Installation

1.  **Clone the repository:**
    bash git clone https://github.com/rsl50/digitsclassifiertf.git

2.  **Open the project in Android Studio:**
    *   Launch Android Studio.
    *   Select "Open an Existing Project."
    *   Navigate to the directory where you cloned the repository and select it.

3.  **Sync the project with Gradle files:**
    *   Click the "Sync Project with Gradle Files" button in the toolbar (it looks like an elephant with a blue arrow).

4.  **Build and run the app:**
    *   Connect your Android device or start an emulator.
    *   Click the "Run" button (green play icon) in Android Studio.

## Project Structure

*   `app/src/main/java/...`: Contains the Kotlin source code for the application.
*   `app/src/main/res/...`: Contains the resources (layouts, drawables, etc.) for the application.
*   `app/src/main/assets/...`: Contains the TensorFlow Lite model file (`.tflite`).
*   `app/build.gradle.kts`: Contains the dependencies and build configurations for the app module.
* `build.gradle.kts`: Contains the dependencies and build configurations for the project.

## Dependencies

*   **TensorFlow Lite:** For running the digit classification model.
*   **AndroidX Libraries:** For modern Android development.
*   **Kotlin Coroutines:** For asynchronous operations.

## TensorFlow Lite Model

The project uses a pre-trained TensorFlow Lite model (`.tflite` file) located in the `app/src/main/assets` directory. This model is optimized for mobile devices and is used for on-device inference.

## Codelab Reference

This project is heavily inspired by and builds upon the concepts presented in the official Android codelab:

*   **Codelab:** [Classify digits with TensorFlow Lite](https://developer.android.com/codelabs/digit-classifier-tflite)
*   **Colab Notebook** [Step 2: Train a machine learning model](https://colab.research.google.com/github/tensorflow/examples/blob/master/lite/codelabs/digit_classifier/ml/step2_train_ml_model.ipynb)
*   **Description:** This codelab guides you through the process of creating an Android app that uses TensorFlow Lite to classify handwritten digits. It covers topics such as model conversion, integration with Android, and on-device inference.

## Contributing

Contributions to this project are welcome! If you find a bug or have an idea for an improvement, please open an issue or submit a pull request.

## License

Apache License, Version 2.0

## Contact

Robson Lima - [GitHub](https://github.com/rsl50) - [Linkedin](https://www.linkedin.com/in/robsonslima/) 