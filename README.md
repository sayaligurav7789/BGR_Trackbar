# BGR Trackbar in Python

A simple Python project that demonstrates the use of OpenCV (`cv2`) and `numpy` to create a BGR (Blue, Green, Red) color trackbar. This project allows the user to adjust the intensity of each color channel (Blue, Green, and Red) in real-time using sliders (trackbars). The resulting color is displayed in an OpenCV window.

## Features

- Interactive trackbars to control the BGR values.
- Real-time updates to the image as you adjust the sliders.
- Simple interface using OpenCV's GUI tools.
- Uses `numpy` to handle the image array manipulation.

## Requirements

- Python 3.x
- OpenCV
- NumPy

You can install the necessary dependencies by running the following:

```bash
pip install opencv-python numpy

```
## How to Run
1. Clone or download this repository to your local machine.
2. Ensure you have the required dependencies installed.
3. Run the script:
   
```bash
python BGR.py
```
This will open an OpenCV window with three sliders for adjusting the Blue, Green, and Red values. As you adjust the sliders, the color of the window will change in real-time based on the BGR values.

## License
This project is open-source and available under the MIT License.
