# Real-Time Color Detector

## Overview

This project implements a **real-time color detection system** that extracts the 7 dominant colors from a webcam feed. 

## Demo!
[![Real-Time Color Detector Demo](https://img.youtube.com/vi/-ZEHrUAASbc/0.jpg)](https://www.youtube.com/watch?v=-ZEHrUAASbc)

## How It Works

1. Capture Frames: The system continuously captures frames from the webcam.
2. Extract Colors: For each frame, 7 most dominant colors are extracted and displayed.
3. Display Colors: These colors are displayed in small boxes on the screen, with their RGB values shown next to each box.
4. Exit the Program: Simply press the q key to stop the program.

## Features
- Real-time color detection from webcam feed.
- Utilizes **OpenCV** library for continuous video capture and display, and **ColorThief** library for color extraction.

## Requirements

- Python 3
- OpenCV (`opencv-python`)
- ColorThief (`colorthief`)

You can install the necessary dependencies with the following commands:

```bash
pip install opencv-python colorthief
