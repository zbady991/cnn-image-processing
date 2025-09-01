# 🖼️ CNN Image Processing Project

This project demonstrates basic **image processing operations** using **OpenCV** and **NumPy**.  
It was originally developed and tested on **Google Colab**, but it can also run locally.  

---

## 📌 Features
The project applies different transformations on an input image (`ele.png`):
1. **Rotation** – Rotates the image by 30° clockwise.  
2. **Translation** – Shifts the image 100px right and 70px down.  
3. **Shearing** – Applies a horizontal shear transformation.  
4. **Normalization** – Normalizes RGB channel values to `[0, 1]`.  
5. **Blurring** – Applies Gaussian blur with a `(3,3)` kernel.  

---

## 🛠️ Requirements
Make sure you have Python 3 installed, then install the required libraries:

```bash
pip install opencv-python matplotlib numpy
