# Lane Detection using Computer Vision

This project focuses on detecting lane lines on roads using computer vision techniques implemented in Python with OpenCV. The goal is to process images or video frames to identify lane markings, which is a crucial component in autonomous driving systems.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Pipeline Overview](#pipeline-overview)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Lane detection is essential for modern driver assistance systems and autonomous vehicles. By identifying lane boundaries, vehicles can maintain proper positioning on the road, enhancing safety and navigation.

## Features

- **Real-time Lane Detection**: Processes video frames to detect lane lines in real-time.
- **Edge Detection**: Utilizes Canny Edge Detection to identify edges in the image.
- **Region of Interest Selection**: Focuses on the relevant part of the image where lane lines are expected.
- **Hough Transform**: Detects lines in the processed image to identify lane markings.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV
  - NumPy
  - Matplotlib

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/anmolsinghdz/Lane-Detection-using-Computer-Vision.git
   cd Lane-Detection-using-Computer-Vision
