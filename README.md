# ANTI THEFT PARCEL DETECTOR
  
This repository contains an Object Detection AI system that can identify and locate parcels within images or video streams. The system is based on state-of-the-art deep learning techniques and is designed for detecting parcels and reducing parcel thefts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Framework Used](#framework-used)
- [Demo](#demo)
- [Installation](#installation)
- [Further Applications](#further-applications)
- [Usage](#usage)

## Introduction

This project aims to create an anti-theft system for parcels delivered to the household.

## Features

- Real-time parcel detection using YOLOV7 framework.
- Customizable model selection and training for specific use cases.
- Easy-to-use Python API for integration into your projects.
- Detailed documentation and example code to get you started.

## Framework Used

Our software uses [YoloV7](https://github.com/WongKinYiu/yolov7) an open source base framework to ease our work with detection and training

## Demo

Here are some images of the model in action.

- Labelling process using `labelimg`:

[![Labelling](https://i.ibb.co/GHMvj3g/Screenshot-2023-11-04-at-7-38-29-PM.png)](https://i.ibb.co/GHMvj3g/Screenshot-2023-11-04-at-7-38-29-PM.png)


- Training process:

[![Training](https://i.ibb.co/yfs9hKJ/Screenshot-2023-11-04-at-7-32-33-PM.png)](https://i.ibb.co/yfs9hKJ/Screenshot-2023-11-04-at-7-32-33-PM.png)

- Working of the model:

[![Working](https://i.ibb.co/h7nQZtv/Screenshot-2023-11-04-at-7-43-38-PM.png)](https://i.ibb.co/h7nQZtv/Screenshot-2023-11-04-at-7-43-38-PM.png)

## Installation

To install and use the anti theft parcel detector, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/siddhantshr/Mirage-Hackathon
   cd Mirage-Hackathon
   ```

2. Install the required dependencies using `pip`:
   ```bash
   pip install -r requirements.txt
   ```

3. The weights have been provided in the yolov7 folder

4. Run the shell code to run the camera.
    ```bash
    ./run.sh
    ```

5. Place a parcel in front of the camera to start Detecting.

## Further Applications

- Due to the limited time, we werent able to push this project to its full potential.

- Our final product would have been a full system integrated with raspberry pi and a camera to run our detection code.

- The user will have to install this system in front of the main door.

- When a package is delivered, the security camera, which is installed at the front door would detect it and transmit a low-level alert to your integrated device.

- Any irregularity in the environment, would have been reported to the owner via its application.

- With the use of a button, the owner would have been able to notify their neighbour or the
community guard.

- The user would also have had the option to examine the camera and make their own
judgements.

## Usage

- Increases security via precise threat detection, and hence benifits both public safety and enterprises.

- Benifits consumers of e-commerce websites by providing an anti-theft system.

- Prevents severe financial strain on victims.

- Motion sensors, tamper-proof packaging, and advanced computer vision algorithms makes it a relaiable system.

---