# WRO 2025 Senior Category - SzbRobot

## Project Overview

This repository contains the code, design documentation, and lessons learned from our team's participation in the World Robot Olympiad (WRO) 2025 Senior Category. Our goal is to provide free and open-source resources to help other teams and individuals learn about building and programming LEGO robots for WRO competitions, particularly focusing on advanced topics like computer vision with TensorFlow Lite.

We believe that access to quality learning materials shouldn't be a barrier to entry in robotics. After the competition, we will be publishing comprehensive guides and explanations based on our experiences.

**Current Status:** **In development.

## Key Technologies Used

* **LEGO Education SPIKE Prime (or other platform used):** The primary robotics platform.
* **Raspberry Pi 5:** Single-board computer for advanced processing and computer vision.
* **Camera Module 3:** For visual input.
* **BuildHAT:** Interface for controlling LEGO motors and sensors with the Raspberry Pi.
* **Python:** The primary programming language.
* **TensorFlow Lite:** For on-device object detection and potentially other computer vision tasks.
* **Full TensorFlow (on PC):** For training the machine learning models.

## Repository Contents (Tentative)

* **`code/`:** Contains the Python code for the robot, including:
    * `main.py`: The main entry point of the robot program.
    * `vision/`: Modules related to computer vision (TensorFlow Lite integration, camera control).
    * `control/`: Modules for motor control, sensor reading, and robot behavior logic.
    * `utils/`: Utility functions and helper classes.
* **`design/`:** Documentation of the robot's mechanical design:
    * `README.md` (in `design/`): Overview of the robot's design principles.
    * `cad/` (Optional): CAD files of the robot (if available and you choose to share).
    * `build_instructions/` (Optional): Step-by-step instructions for assembling key parts of the robot.
* **`models/`:** (After competition, potentially) Contains the TensorFlow Lite models used (or instructions on how to train them).
* **`data/`:** (Potentially) Information about the training datasets used for the TensorFlow models (without sharing the raw data itself, due to size and privacy).
* **`documentation/`:** More detailed explanations, tutorials, and lessons learned.
    * `lessons_learned.md`: A summary of challenges and solutions.
    * `computer_vision_guide.md`: Detailed explanation of our TensorFlow Lite implementation.
    * `robot_design_rationale.md`: Explanation of our design choices.
* `README.md`: This file.
* `LICENSE`: Specifies the open-source license under which the resources are shared.

## Getting Started (For After the Competition)

After WRO 2025, this section will be expanded with detailed instructions on how to use the resources in this repository. This will likely include:

* Instructions on setting up the Raspberry Pi 5 with the necessary software.
* Steps for installing the required Python libraries (TensorFlow Lite runtime, BuildHAT).
* Guidance on understanding and running the provided code.
* Information on training your own TensorFlow Lite models (if applicable).
* Explanations of the robot's mechanical design and assembly.


## License

This project will be shared under an open-source license. We are considering MIT

## Team Information

* **Team Name:** SzbRobot
* **WRO 2025 Category:** Senior
* **Country:** Germany
* **Y. & T.**


---

As you progress, keep this README updated. It will serve as the introduction to your project for anyone who finds it later. Good luck with your WRO 2025 journey! I'm here to help you fill in the details and expand on any of these sections as you go.
