# Automatic-Number-Plate-Recognition-System

This project detects, tracks, and recognizes license plates in vehicle videos using **YOLOv8**, **EasyOCR**, **SORT tracking**, and **OpenCV**. It draws bounding boxes around vehicles and license plates, tracks vehicles across frames, and overlays the recognized license plate text on the video.

---

## 🔧 Requirements

Install dependencies using: pip install -r requirements.txt

---

## 🧠 Model Details

YOLOv8: Detects cars and license plates.

SORT Tracker: Assigns consistent IDs to moving vehicles.

EasyOCR: Recognizes text from license plates.

OpenCV: Video processing and annotation.

---

## ✨ Features

🚘 Detects and tracks multiple vehicles

🔢 Extracts and recognizes license plate numbers

🎨 Draws styled borders and overlays plate crops

🎥 Outputs clean, annotated video

📈 Handles missed detections using interpolation

---

## 🔍 Example Output

Annotated vehicle bounding boxes with borders

License plate bounding boxes

Recognized plate number text

Cropped license plate previews on video


![Screenshot 2025-05-16 173359](https://github.com/user-attachments/assets/4c7e8b44-e923-43aa-b7fb-ae855008503e)

---

## 🙌 Acknowledgments

Ultralytics YOLOv8

EasyOCR

SORT algorithm for tracking

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change or add.

---

### Made with ❤️ by Shrestha!



