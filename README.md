# Image Viewer Project

This is a simple image viewer application built using Python's tkinter and PIL (Pillow) libraries. It allows you to view a series of images and navigate through them using forward and backward buttons.

## Prerequisites

Before running the application, ensure you have the following:

- Python installed on your system.
- The tkinter library (usually included with Python).
- The Pillow (PIL) library for working with images. You can install it using pip:

```bash
pip install pillow
```

## Usage

1. Clone or download this repository to your local machine.
2. Place the images you want to view in the same directory as the Python script. Make sure to name them "img1.jpg," "img2.jpg," and so on, or update the script with the appropriate image filenames.
3. Run the Python script to start the image viewer application:

```bash
python image_viewer.py
```

1. The application window will appear, displaying the first image in the series.
2. Use the following buttons to navigate:
   - **Back:** Move to the previous image.
   - **Forward:** Move to the next image.
   - **Exit:** Close the application.
   
## Code Explanation

The code uses tkinter for creating the graphical user interface and PIL (Pillow) for working with images. Here's a brief explanation of the code's structure:

- Import necessary libraries.
- Define functions for moving forward and backward through the images.
- Create a tkinter window.
- Load the images using Pillow's ImageTk.PhotoImage.
- Display the first image and set up buttons for navigation.
- Start the tkinter main loop.
