# Punch My Professors - McGill McHacks 11

## Introduction
Welcome to Punch My Professors, an exciting Unity app developed for McGill McHacks 11. This repository contains the source code and necessary dependencies to build and run the app.
<iframe width="560" height="315" src="https://www.youtube.com/embed/pnxXGGBSUc0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<img width="1708" alt="image" src="https://github.com/user-attachments/assets/3bb30c85-0928-4f8f-a649-c6c165299ca2">

## Contents
1. **McHacks:** This folder contains essential files and assets required for the McGill McHacks 11 integration.
2. **Menu:** The Menu folder holds additional dependencies that contribute to the functionality and user interface of the app.
3. **MeshyAPI**: This folder contains the API which converts a 2d image to a 3D FBX file to be used in-game.
4. **Output:** This folder is designated for storing the output generated by building the app in Unity.

5. ## Technologies Used

Punch My Professors is developed using a combination of versatile technologies to create an engaging and dynamic experience.

- **Unity:** The app is built using the Unity game development engine, providing a powerful and flexible platform for creating immersive applications.
- **C#:** The primary programming language for developing the logic and functionality of the Punch My Professors app within the Unity framework.
- **Python:** Python is employed for various scripting and backend functionalities, enhancing the app's overall capabilities, specifcally the API which communicates with Imgur API and Meshy API.
- **OpenCV:** OpenCV (Open Source Computer Vision Library) is utilized to incorporate computer vision features, enabling image processing and analysis of the user's hand within the app.
- **Tensorflow:** Leveraging the capabilities of TensorFlow, an open-source machine learning framework, Punch My Professors integrates machine learning models to enhance certain aspects of the application, specifically the hand-recognition.

## Getting Started
To launch Punch My Professors, follow these simple steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Punch-My-Professors.git

2. **Navigate to the Repository:**
   ```bash
   cd Punch-My-Professors

3. **Run the App:**
   Open the file PunchMyProf.bat to launch the app.

## Important Note
1. This app was developed specifically for McGill McHacks 11, and certain functionalities may be tailored to the event's requirements.
2. The custom feature of this app will not function natively if the API keys are not included in the Unity build. A config file called config.py should be placed during the build in the same directory as main.py to allow the custom character feature to work.
(If no API keys are provided, the app will default to a sepcific picture posted on Meshy API)

## Contributing
If you would like to contribute to Punch My Professors or report any issues, feel free to create a pull request or open an issue on our GitHub repository.

## Acknowledgments
Thank you for checking out Punch My Professors. We hope you enjoy the app and find it amusing. Happy hacking!
