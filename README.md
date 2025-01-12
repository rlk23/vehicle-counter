# 🚗 Vehicle Counter: AI-Powered Traffic Monitoring

The **Vehicle Counter** is a cutting-edge program designed for real-time vehicle detection and tracking. By leveraging **background subtraction** and the powerful **dlib correlation tracker**, this application enables accurate and efficient counting of vehicles passing through a designated area. Its modular design makes it easy to extend with advanced object detection frameworks like YOLO or HOG+SVM.

---

## 🔍 Features

- **Real-Time Tracking**: Monitor and count vehicles in live or pre-recorded video feeds.
- **Highly Modular**: Replaceable object detectors (YOLO, HOG+SVM, etc.).
- **Accurate Detection**: Uses background subtraction for detecting objects in motion.
- **Customizable**: Easy to configure for different environments and scenarios.
- **Lightweight and Efficient**: Designed for low-latency performance on edge devices.

---

## 🛠 Requirements

Ensure the following dependencies are installed:

1. `opencv==4.2.0`
2. `dlib==19.17.0`
3. `numpy` (for array operations)
4. `imutils` (for streamlined OpenCV functions)

