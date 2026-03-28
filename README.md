# image-audio-processing-knn

This project implements a multimedia processing system in Python, including image processing, audio manipulation, and a K-Nearest Neighbors (KNN) classifier for image classification. It also includes an interactive image viewer for visualization.

## 🚀 Features

### Image Processing
- RGB image abstraction with validation and deep copy support
- Image transformations:
  - Negation
  - Grayscale conversion
  - Rotation (180°)
  - Brightness adjustment
- Advanced processing:
  - Pixelation
  - Edge highlighting

### Audio Processing
- Reverse audio signals
- Slow down and speed up playback
- Add reverb/echo effects
- Clip segments of audio

### Machine Learning (KNN)
- Implemented a **K-Nearest Neighbors classifier from scratch**
- Custom Euclidean distance over RGB pixel values
- Majority voting for prediction
- Supports training on labeled image datasets :contentReference[oaicite:0]{index=0}  

### Interactive Image Viewer
- Zoom and pan functionality
- Real-time pixel color inspection on hover
- Built using Tkinter for visualization :contentReference[oaicite:1]{index=1}  

---

## 🧠 Key Concepts Demonstrated
- Object-Oriented Programming (OOP)
- Data structures and abstraction design
- Image and signal processing
- Machine learning fundamentals (distance-based classification)
- Algorithm implementation from scratch
- GUI development with Tkinter

---

## 📁 Project Structure
project.py # Core implementation (image, audio, KNN)
image_viewer.py # Interactive image viewer (Tkinter GUI)
