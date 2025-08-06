# 🕳️ Pothole Detection System using Deep Learning

This project is a real-time **pothole detection system** using computer vision and deep learning. It processes frames from a dashcam video and detects potholes with a pre-trained model. When a pothole is detected with high confidence, the system displays a warning and plays a beep sound.

---

## 🎯 Features

- 🔍 Detects potholes in video frames using a trained CNN model
- 🎵 Plays a warning sound when a pothole is detected
- 📺 Displays the video feed with overlayed detection results
- 🖼️ Optional GUI version using Tkinter for real-time monitoring

---

## 🧠 Tech Stack

- **Python**
- **OpenCV** – for video frame processing
- **TensorFlow/Keras** – to load and run the trained deep learning model
- **NumPy** – for array and image manipulation
- **Pygame** – for audio alert playback
- **Tkinter** (optional) – for graphical interface version
- **Pillow** – image conversion for Tkinter (GUI version only)

---

## 📁 File Structure

```
├── model2.h5                   # Trained Keras model for pothole detection
├── beep.mp3                   # Beep sound for pothole alert
├── pothole_detection.py       # Console-based version (with OpenCV and Pygame)
├── pothole_gui.py             # GUI version with Tkinter
├── requirements.txt           # Python dependencies
├── README.md                  # Project overview
```

---

## 🚀 How to Run

1. **Clone the repository** and navigate into it:
   ```bash
   git clone https://github.com/your-username/pothole-detection.git
   cd pothole-detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script**:

   - For the **console-based version**:
     ```bash
     python pothole_detection.py
     ```

   - For the **GUI version** (Tkinter):
     ```bash
     python pothole_gui.py
     ```

---

## 📝 Requirements

See `requirements.txt` for all packages:
```
opencv-python
numpy
pygame
tensorflow
pillow
```

---

## 📌 Notes

- Make sure to update the paths in the code to match your model, video, and sound file locations.
- Trained model (`model2.h5`) should be placed in the same directory unless otherwise specified.
- Requires Python 3.7 or higher.

---

## 👩‍💻 Author

**Deepthi Dasari**  
Deep Learning & Computer Vision Enthusiast

---

## 📜 License

This project is for academic and demonstration purposes. Feel free to use or modify it for learning.
