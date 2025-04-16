# Image Processing GUI App 🎨🖼️

This project is a **Tkinter-based Image Processing Application** using Python. It provides a simple GUI for applying common image processing techniques such as thresholding, edge detection, histogram equalization, and power-law transformation using OpenCV and Pillow.

---

## 📌 Features

- 📂 Load and display original and processed images side by side
- 🎚 Threshold-based segmentation with slider control
- ✂ Edge segmentation using Canny + dilation
- 📈 Histogram equalization
- ⚡ Power-law (gamma) transformation with interactive input
- 📊 Real-time image updates
- 🪟 Clean and styled interface with status messages

---

## 🛠 Tech Stack

- Python 3
- Tkinter (GUI)
- OpenCV (`cv2`)
- Pillow (`PIL`)
- NumPy

---

## 🚀 How to Run

1. Clone this repository or copy the script to your machine.
2. Ensure the following packages are installed:
```bash
pip install opencv-python pillow numpy
```
3. Run the script:
```bash
python image_processing_gui.py
```

---

## 📸 GUI Preview

> Replace the placeholder with your own screenshot.

![App Screenshot](https://i.imgur.com/YOUR_SCREENSHOT.png)

---

## ⚠ Warnings

- Uses `Image.LANCZOS`, which is deprecated and will be removed in Pillow 10. Replace it with `Image.Resampling.LANCZOS` for future compatibility.
- This script does not save the processed image.

---

## 📂 File Structure

```
image_processing_gui.py     # Main script for GUI and processing
README.md                   # Project overview
```

---

## 📬 Contact

For any queries or suggestions, feel free to reach out!

---

Happy Coding! 💻🧠🎉
