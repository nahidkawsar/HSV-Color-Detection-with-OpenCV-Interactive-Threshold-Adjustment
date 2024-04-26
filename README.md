# HSV Color Detection with OpenCV: Interactive Threshold Adjustment
This Python script detects colors in a live video stream using HSV (Hue, Saturation, Value) color space. It allows users to adjust the lower and upper HSV thresholds interactively with trackbars.

## Requirements
* Python 3.x
* OpenCV (cv2)
* numpy

## Installation
Clone the repository to your local machine:

git clone https://github.com/your_username/screen-recording-python.git


## Usage
* Make sure you have Python and the required libraries installed.
* Run the script.
* Adjust the trackbars to set the lower and upper HSV thresholds for the color you want to detect.
* The script will display the original video feed, the mask showing the detected color, and the final image with the detected color highlighted.

## Trackbars

* Lower_H, Upper_H: Adjust the lower and upper values for the Hue channel.
* Lower_S, Upper_S: Adjust the lower and upper values for the Saturation channel.
* Lower_V, Upper_V: Adjust the lower and upper values for the Value channel.

## How It Works
* The script captures video from your webcam.
* It converts each frame from BGR to HSV color space.
* It creates a mask using the lower and upper HSV thresholds set by the user.
* The script displays the original frame, the mask, and the final image with the detected color.

Author
H.M Nahid Kawsar
LinkedIn:linkedin.com/in/h-m-nahid-kawsar-232a86266

Sample:![Thumbnil](https://github.com/nahidkawsar/HSV-Color-Detection-with-OpenCV-Interactive-Threshold-Adjustment/assets/149723828/25c1b4a8-c984-47fc-8872-bf2687ea90df)
