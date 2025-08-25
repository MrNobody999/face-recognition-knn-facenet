# Face Recognition with KNN + FaceNet + MongoDB

This project implements a simple **face recognition system** using:
- **MTCNN** for face detection
- **InceptionResnetV1 (FaceNet)** for embeddings
- **K-Nearest Neighbors (KNN)** for classification
- **MongoDB** for storing and retrieving test embeddings

---

##  Project Structure
face-recognition-knn-facenet/
│
├── enroll/ # Training dataset (organized by person)
├── models/ # Trained KNN model gets saved here
├── scripts/ # Training & Inference scripts
├── test_images/ # Example test images
├── requirements.txt
├── README.md
└── .gitignore


---

## ⚙️ Installation

Clone the repo and install dependencies:
```bash
git clone https://github.com/<your-username>/face-recognition-knn-facenet.git
cd face-recognition-knn-facenet
pip install -r requirements.txt

