# Real-Time Face Recognition with KNN

This project demonstrates a real-time face recognition system using the K-Nearest Neighbors (KNN) algorithm with OpenCV. It includes steps to collect face data, train the model, and perform real-time face recognition via webcam.

## 🚀 Features

- Real-time face detection using Haar Cascades
- Data collection from webcam (selfies)
- Face data preprocessing and organization
- Face recognition using a simple KNN classifier
- Jupyter Notebooks to showcase each step clearly

## 📂 Project Structure

```
real-time-face-recognition-with-knn/
│
├── haarcascade_frontalface_alt.xml        # Haar Cascade classifier file
├── image_folder/                          # Contains sample face images
├── selfies_training_data/                 # Stores collected face data
│
├── OpenCV-working with video stream from webcam.ipynb
├── cv2 with plt.ipynb
├── face detection using haarCascades.ipynb
├── generating selfies.ipynb
├── image show using cv2.ipynb
├── predicting name from face .ipynb
└── README.md
```

## 🛠️ Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

### 📦 Installation

Use pip to install the required libraries:

```bash
pip install opencv-python numpy matplotlib
```

## 📸 Usage Guide

### 1. Data Collection
Run `generating selfies.ipynb` to collect selfies using your webcam. These will be saved in `selfies_training_data/`.

### 2. Face Detection
Use `face detection using haarCascades.ipynb` to verify if face detection works correctly with your setup.

### 3. Training & Prediction
Open `predicting name from face .ipynb` to process collected data and train a KNN model to recognize the faces.

### 4. Real-Time Face Recognition
Launch `OpenCV-working with video stream from webcam.ipynb` to see the real-time recognition in action.

## 📌 Notes

- Ensure proper lighting during data collection for best results.
- You can increase the number of images per person to improve accuracy.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Built with ❤️ using Python & OpenCV
