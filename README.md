# Vehicle-Counting
## YOLOv7-DeepSORT Vehicle Detection and Tracking
This repository contains Python code for implementing YOLOv7 (You Only Look Once) object detection algorithms in PyTorch. The primary goal of this project is to detect and track vehicles in traffic surveillance video footage, utilizing the YOLO algorithm for detection and the DeepSORT (Deep Simple Online and Realtime Tracking) algorithm for tracking.

![alt text](https://github.com/IsaiasNegassi/Vehicle-Counting/blob/main/photo2.png)
![alt text](https://github.com/IsaiasNegassi/Vehicle-Counting/blob/main/photo1.png)


## Features:
* Object Detection: The code includes a detector module capable of detecting various objects, including persons, horses, and sports balls. You can configure the detector to detect specific classes or all available classes.
* YOLOv7 Implementation: The repository provides scripts to load and utilize pre-trained YOLOv7 weights for object detection tasks.
* DeepSORT Integration: The implementation includes integration with the DeepSORT algorithm for object tracking. DeepSORT combines deep learning-based object detection with a sophisticated online tracking algorithm for robust and efficient tracking of objects over time.
* Counting and Analysis: Additionally, the code includes functionality for counting the number of vehicles that cross a specified line in the surveillance footage. It utilizes trajectory analysis to determine when vehicles cross the designated line and provides visualizations and data analysis for further insights.

## Instructions running the code
1. Clone the repository and install the required dependencies.
2. Load the pre-trained YOLOv7 weights for object detection.
3. Configure the tracking parameters and initialize the YOLOv7-DeepSORT tracker.
4. Run the tracking module on your surveillance video footage.
5. Analyze the output, including vehicle count and trajectory data, for insights into traffic patterns and behavior.

## Example Application:
The repository includes scripts for processing real-world traffic surveillance video footage, analyzing vehicle movements, and generating vehicle count statistics. You can customize the code to suit your specific surveillance scenarios and analysis requirements.

## Dataset and Evaluation:
The code is designed to work with traffic surveillance video footage, but it can be adapted to other datasets and scenarios as needed. It provides tools for evaluating detection and tracking performance and supports integration with custom datasets for training and testing.
## Contributions:
Contributions and feedback are welcome! Feel free to submit pull requests, open issues, or reach out with any questions or suggestions.
