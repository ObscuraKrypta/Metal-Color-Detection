# PiVisionSort: Integrating Image Processing and Machine Learning for Material Recognition on Conveyor Belts
PiVisionSort is an advanced system for the automatic detection of different materials on a conveyor belt that uses image processing and machine learning techniques. The project aims to improve efficiency and accuracy in industrial recycling processes, especially for identifying metals such as aluminium, copper and brass. Using a Raspberry Pi and a camera, this system performs real-time material detection based on color and texture characteristics, providing robust and consistent performance in a variety of industrial conditions.

# Features
- Material detection: automatic identification and classification of materials passing on the conveyor.
- Support for different metals: The ability to identify aluminum, copper and brass using image processing and K-means clustering.
- Integration with machine learning: Using decision trees to optimize material classification accuracy.

# How to apply the project:
Please follow the instruction.
# 1- lsm_beforewebcam.py 
The main script that processes the conveyor images and applies machine learning algorithms to classify the material.
# 2- Data set
Includes aluminum, copper and brass related data for training and testing machine learning models.
# Prerequisites
Before running this script, ensure you have the following hardware and software:

# Hardware
- Raspberry Pi (with GPIO capabilities)
- An ELP camera
- An infrared light barrier sensor

## Software
- Python 3.x
- Required Python libraries:
  - opencv-python 
  - numpy 
  - scikit-learn
  - matplotlib
  - pandas
 
# Note:
- To send alerts, you need to create a bot in Telegram. Get a token for a bot through BotFather on Telegram.
- Chat IDs of users receiving alerts (including yourself) are also required.
Good luck with creating the bot :) 

## Installation
Install the required Python libraries using pip:

```sh
pip install opencv-python
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install pandas
```

## Software installation and configuration
1- Install Python and required libraries
```sh
sudo apt install python3 python3-pip -y
```
6- Run the file -> lsm_beforewebcam.py 


































