# Face Detection App

This **Face Detection App** is built using **Streamlit** and **OpenCV**, designed to offer users a range of image processing capabilities, including face detection, smile detection, eye detection, and image enhancements. The app also includes artistic transformations like cartoonizing and edge detection (Canny).


https://github.com/user-attachments/assets/fe2160d4-5b24-4fdf-8552-44baedacf667


---

## Features

- **Face Detection**: Detects faces within uploaded images.
- **Eye Detection**: Identifies eyes in the image.
- **Smile Detection**: Detects smiles for more engaging photos.
- **Cartoonize Image**: Converts an image into a cartoon-style picture.
- **Edge Detection**: Applies Canny edge detection to highlight outlines.
- **Image Enhancement**:
  - **Gray-Scale**: Converts the image to grayscale.
  - **Contrast**: Adjusts the contrast of the image.
  - **Brightness**: Allows users to adjust the brightness.
  - **Blurring**: Applies a Gaussian blur to the image.

---

## Requirements

To run this app, you need to install the following Python libraries:

- **Streamlit**: To create the user interface.
- **OpenCV**: For face, smile, and eye detection.
- **Pillow**: For image processing and enhancement.
- **NumPy**: To handle image arrays.

## Installation

1. **Clone this repository** to your local machine:

```bash
git clone https://github.com/your-username/face-detection-app.git
cd face-detection-app
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**:

```bash
streamlit run app.py
```

## How to Use

1. **Upload an Image**: Select an image file (JPG, PNG, JPEG) from your local system.
2. **Enhance Image**: Choose between different enhancement options like Gray-Scale, Contrast, Brightness, and Blurring.
3. **Detect Features**: Select from the available options to detect faces, eyes, or smiles in the image.
4. **Cartoonize or Apply Edge Detection**: Transform your image into a cartoon or apply Canny edge detection.
5. **Download the Result**: Once the image is processed, you can download the modified image by clicking the "Download" button.

---

## About the Developer

This app was built by **Apeksha Chandak**, a passionate software developer with a focus on AI and computer vision. The goal is to create accessible and interactive tools for image processing, with an easy-to-use interface built using Streamlit.

---

## Acknowledgements

- **OpenCV**: [OpenCV Library](https://opencv.org/)
- **Streamlit**: [Streamlit Website](https://streamlit.io/)
- **Haar Cascades**: Used for face, smile, and eye detection.

---


### **`requirements.txt` file**:

For completeness, here’s what the `requirements.txt` file should look like:

```
streamlit
opencv-python
numpy
pillow
```

---

### **Customization and Contributions**

Feel free to fork this repository, submit issues, or contribute improvements. I welcome pull requests to make this app better and more feature-rich!

---
