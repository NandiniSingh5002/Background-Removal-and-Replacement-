# Background Removal and Replacement using Python

## 📌 Project Overview

This project uses Python, OpenCV, and CVZone's Selfie Segmentation module to remove the background from an image of a person and replace it with a custom background image.

The project uses machine learning-based segmentation to identify the person and separate them from the original background.

## ✨ Features

- Removes the original background from an image.
- Replaces the background with a custom image.
- Uses CVZone's Selfie Segmentation module.
- Resizes images to maintain compatible dimensions.
- Displays the final output using OpenCV.

## 🛠️ Technologies Used

- **Python** – Programming language.
- **OpenCV (`cv2`)** – Image processing and display.
- **CVZone** – Selfie segmentation functionality.
- **NumPy** – Array and image processing operations.

## 📂 Project Structure

```text
Background-Removal/
│
├── BackgroundImages/
│   └── 1.jpg
│
├── view1.jpeg
├── main.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Background-Removal
```

### 2. Install the required libraries

```bash
pip install opencv-python cvzone mediapipe numpy
```

## 🚀 How to Run

1. Place the original image (`view1.jpeg`) in the project directory.
2. Place your replacement background image inside the `BackgroundImages` folder.
3. Ensure that the image paths in the Python script are correct.
4. Run the script:

```bash
python main.py
```

5. A window will display the image with its background replaced.

## 🔍 How It Works

1. Loads the original image and replacement background.
2. Resizes both images to compatible dimensions.
3. Initializes the CVZone Selfie Segmentation model.
4. Detects the person and separates them from the background.
5. Replaces the original background with the selected image.
6. Displays the final result using OpenCV.

## 🎯 Use Cases

- Photo background replacement.
- Basic image editing applications.
- Computer vision learning projects.
- Background customization for portraits.
- A foundation for real-time webcam background replacement.

## 🔮 Future Improvements

- Add support for transparent PNG output.
- Allow users to select backgrounds dynamically.
- Process multiple images in batches.
- Implement real-time background replacement using a webcam.
- Improve segmentation quality around hair and object edges.

## 👨‍💻 Author

Nandini Singh

## 📄 License

This project is intended for educational and personal use. Add a suitable open-source license if you plan to distribute it publicly.
