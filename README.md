# CamShift Object Tracking Project

A Python project that utilizes OpenCV to create a CamShift object tracking system.

## Requirements

* Python 3.x
* OpenCV
* NumPy

## Setup

1. Install the required packages using pip:
   ```bash
    pip install opencv-python numpy
    ```

## Usage

1. Clone the repository to your local machine using Git:
   ```bash
    git clone https://github.com/bkk31/camshift.git
    ```
2. Navigate to the project directory:
   ```bash
    cd camshift
    ```
3. Run the Python script using Python 3.x:
   ```bash
    python main.py
    ```

## Notes

* This project uses OpenCV for image processing and CamShift algorithm for object tracking.
* Make sure to check the library documentation for any updates or changes to the API.
* Also, ensure that the video capture device is properly configured and connected.

## Important Note: 
* The CamShift algorithm in this project has been observed to work remarkably well on tracking human faces, providing accurate and smooth tracking results. 
* However, its performance on tracking generic objects is somewhat limited, and may not always produce optimal results. 
* This is due to the inherent characteristics of the CamShift algorithm, which is more suited for tracking objects with distinct color and texture features, such as human faces.

## License

This project is licensed under the GNU General Public License version 3.0 (GPLv3). See the LICENSE file for details.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.