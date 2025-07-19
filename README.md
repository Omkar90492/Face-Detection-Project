# 🧠 Face Detection Using OpenCV

A computer vision project that detects human faces in images using OpenCV’s Haar Cascade Classifier.

This repository includes:

- Pre-trained Haar Cascade XML files for frontal face detection
- A Python script to process images and detect faces
- Sample input and output images for demonstration
- Folder structure for storing datasets, results, and documentation

---

## ⚙️ Features

✅ Detects faces in images using Haar Cascades  
📸 Processes multiple input images automatically  
📝 Includes pretrained models (Haar cascades)  
💾 Saves detected face images as output  
💡 Easy to integrate with GUI/web camera feed

---

## 📁 Project Structure

`face_detect.py` — Main face detection script  
`Cascades/` — Haar cascade XML files  
`images/` — Sample input images  
`Weights/` — Additional trained weights (optional)  
`Data Set/` — Dataset for testing  
`Docs/` — Project documentation  

---

## 🧠 Tech Stack

- **Python 3.7+** – Programming language  
- **OpenCV** – Image processing and face detection  
- **NumPy** – Array and image data manipulation  
- **Haar Cascade** – Pre-trained XML face classifier  
- **Matplotlib** – Optional: visualize images and bounding boxes  

---

## 🚀 How to Run the Project

Follow these steps to set up and run the project locally:

### Step 1: Clone the Repository

git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name

---

### Step 2: Install the Required Dependencies

pip install -r requirements.txt

---

### Step 3: Run the Main Script

python face_detect.py

---

### Step 4: Output
The script will:

Load sample images from the /images folder

Detect faces using the Haar cascade model

Draw bounding boxes around detected faces

Save output images to a new folde

