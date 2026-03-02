**🐝 Stingless Bee Image Classification & Detection**
Sistem klasifikasi dan deteksi spesies lebah madu tanpa sengat (stingless bee) menggunakan Deep Learning.
Project ini mengimplementasikan DenseNet121 untuk klasifikasi citra dan YOLOv9 untuk deteksi objek berbasis bounding box.

**📌 Project Overview**
Identifikasi spesies secara manual masih bergantung pada keahlian khusus dan berpotensi menimbulkan kesalahan.
Project ini bertujuan untuk mengembangkan sistem otomatis berbasis Computer Vision untuk:
🔍 Mengklasifikasikan spesies lebah tanpa sengat
📦 Mendeteksi objek lebah menggunakan bounding box
📊 Membandingkan performa pada ukuran input berbeda (224×224 dan 640×640)

Dataset terdiri dari 1.470 citra yang terbagi ke dalam 7 kelas spesies.

**🧠 Model Architecture**
1️⃣ Classification Model
Model: DenseNet (DenseNet121)
Input size:
224×224
640×640

Approach:
Hybrid prediction berbasis embedding
DLS (Distance Learning Similarity) index

2️⃣ Detection Model
Model: YOLO (YOLOv9)
Menggunakan data beranotasi bounding box

Input size:
224×224
640×640

**🔄 Data Augmentation**
Teknik augmentasi yang digunakan pada seluruh eksperimen:
Horizontal & vertical flipping
Brightness adjustment
Random cropping
