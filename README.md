# Invisibility Cloak (OpenCV)

A real-time "invisibility cloak" built with Python, OpenCV and NumPy. A red object (here, the Tunisian flag) is detected by colour and replaced with the saved background, so it disappears on the live video.

## How it works
1. Capture the background frames from the webcam.
2. Convert each live frame to HSV and mask the red range.
3. Smooth the mask (morphological operations).
4. Replace the masked pixels with the saved background.

## Tech
Python, OpenCV, NumPy

## Demo
LinkedIn video: https://www.linkedin.com/in/chamseddinehammami/ (post from December 2025)

## Run
Open `invisibility_cloak.ipynb` in Jupyter and run all cells with a webcam connected.
