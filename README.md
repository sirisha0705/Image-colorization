# Image Colorization Using U-Net–Like Generator

This project focuses on automatic **image colorization**, where grayscale images are converted into realistic color images using a **U-Net–like deep learning generator**. The model learns both low-level spatial details and high-level semantic features to predict color information.

---

## Overview

Image colorization is a challenging computer vision task because multiple color interpretations are possible for a single grayscale image. This project uses a U-Net–style encoder–decoder architecture with skip connections to preserve image structure while generating accurate color outputs.

---

## How It Works

- Input color images are converted to grayscale  
- The grayscale image is fed into a U-Net–like generator  
- The encoder extracts multi-scale features  
- Skip connections retain spatial details  
- The decoder reconstructs color channels  
- The output is a colorized image  

---

## Technologies

Python, Deep Learning, TensorFlow/Keras, NumPy, OpenCV, Matplotlib

---
## Project Structure


Image Colorization using U-Net/

train.py # Model training script

test.py # Model testing / inference

model.py # U-Net–like generator definition

requirements.txt # Python dependencies

dataset/ # Training and testing images

saved_models/ # Trained model weights

outputs/ # Colorized output images

README.md

---

---

## How to Run
pip install -r requirements.txt

python train.py

python test.py

