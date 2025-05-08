
# 🚗 Vehicle Detection and Counter using OpenCV

This project detects and counts vehicles in a video using background subtraction and contour detection techniques with OpenCV.

---

## 📌 Features

- Detect moving vehicles using MOG (Mixture of Gaussians) background subtraction
- Track and count vehicles as they cross a designated line
- Real-time video processing using OpenCV
- Displays bounding boxes, centers, and vehicle count on frames

---

## 🎯 Requirements

- Python 3.x
- OpenCV (`opencv-python`, `opencv-contrib-python`)
- Numpy

---

## 🛠️ Installation

```bash
pip install opencv-python opencv-contrib-python numpy
````

---

## 📂 Folder Structure

```
vehicle_detection/
├── video.mp4                # Input video for vehicle detection
├── vehicle.py                  # Main script file
├── README.md                # Project documentation
```

---

## 🚀 How to Run

```bash
python vehicle.py
```

> Replace `video.mp4` with your own video if needed.

---

## 📸 Output

* Vehicles are highlighted with bounding boxes.
* Center points are marked.
* A line is drawn to count vehicles when crossed.
* Live counter is displayed on screen.

---

## 🧠 How It Works

1. Read video frames using OpenCV.
2. Convert to grayscale and apply Gaussian Blur.
3. Use MOG background subtraction to identify motion.
4. Apply morphological operations to remove noise.
5. Detect contours and draw bounding boxes around vehicles.
6. Track vehicle center points and count them when they cross a line.

---

## 📽️ Example

![Demo GIF or Screenshot here](demo.gif)
![Screenshot 2025-05-08 163629](https://github.com/user-attachments/assets/40cefa5d-ead5-4271-8a25-61e658cff2e7)


