
# Smart Vision Drop Dispenser

## Overview

Smart Vision Drop Dispenser is a computer vision-based assistive healthcare device designed to automate eye-drop administration for elderly individuals, visually impaired patients, and users with motor impairments. The system utilizes Raspberry Pi, OpenCV, and a servo-controlled dispensing mechanism to ensure accurate and hygienic eye-drop delivery.

## Problem Statement

Manual eye-drop administration can be challenging and may result in:

* Incorrect drop placement
* Medicine wastage
* Contamination of the bottle tip
* Difficulty for elderly or physically challenged users

This project aims to provide a hands-free and automated solution for accurate eye-drop dispensing.

## Features

* Real-time eye detection using OpenCV
* Automated eye-drop dispensing using SG90 servo motor
* Raspberry Pi-based image processing and control
* Audio feedback through buzzer notification
* Reduced medicine wastage and improved hygiene
* User-friendly and assistive healthcare design

## Tech Stack

### Hardware

* Raspberry Pi 4
* Raspberry Pi Camera Module
* SG90 Servo Motor
* Buzzer
* Eye-drop dispensing mechanism

### Software

* Python
* OpenCV
* Raspberry Pi OS
* RPi.GPIO Library

## System Workflow

1. Camera captures real-time images of the user's eye.
2. OpenCV processes the captured frames.
3. Eye position is detected and verified.
4. Raspberry Pi generates PWM signals through GPIO pins.
5. Servo motor actuates the dropper mechanism.
6. Eye drop is dispensed.
7. Buzzer provides confirmation feedback.

## Project Architecture

Camera Module → Raspberry Pi → OpenCV Eye Detection → Servo Motor Control → Eye Drop Dispensing → Buzzer Feedback

## Results

* Successfully demonstrated automated eye-drop dispensing.
* Improved dispensing accuracy through vision-based alignment.
* Reduced dependency on hand-eye coordination.
* Published at an IEEE Conference (2025).
* Secured KSCST funding for project development and implementation.

## Future Enhancements

* AI-based eye tracking and alignment
* Mobile application integration
* Voice-guided assistance
* Portable battery-powered design
* Dose tracking and reminder system

## Contributors

Monika D A 
Nirmala A R
Parinitha P
Preethi H R

## License

This project is intended for academic and research purposes.
