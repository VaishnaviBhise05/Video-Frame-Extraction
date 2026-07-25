# 🎥 Video Frame Extraction using OpenCV

## 📌 Overview

This project demonstrates how to extract frames from a video using Python and OpenCV. It reads a video file, saves each frame as an individual image, and allows the user to display a specific frame from the video.

This project is useful for beginners learning computer vision, video processing, and OpenCV.

---

## ✨ Features

- Extracts all frames from a video.
- Saves each frame as a JPG image.
- Automatically creates an output folder if it does not exist.
- Displays a selected frame from the video.
- Simple and easy-to-understand Python code.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- OS Module
- Google Colab (for image display)

---

## 📂 Project Structure

```
Video-Frame-Extraction/
│
├── extract_frames.py
├── README.md
└── sample_video.mp4 (optional)
```

---

## ▶️ How to Run

1. Install OpenCV:

```bash
pip install opencv-python
```

2. Place your video file in the project folder.

3. Update the video path in the Python file.

```python
video_path = "your_video.mp4"
```

4. Run the script:

```bash
python extract_frames.py
```

5. The extracted frames will be saved in the **data/** folder.

---

## 📸 Output

- Extracted frames are saved as:

```
data/frame0.jpg
data/frame1.jpg
data/frame2.jpg
...
```

- The selected frame is displayed on the screen.

---

## 📚 Learning Outcomes

This project helps in understanding:

- Video processing using OpenCV
- Reading videos frame by frame
- Saving images using Python
- File and folder handling
- Basic computer vision concepts

---

## 🚀 Future Improvements

- Extract every Nth frame.
- Resize frames before saving.
- Save frames in different image formats.
- Create a simple GUI.
- Process live webcam video.

---

## 👩‍💻 Author

**Vaishnavi Bhise**

GitHub: https://github.com/VaishnaviBhise05
