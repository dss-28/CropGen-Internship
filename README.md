# 🌱 CropGen - Plant Disease Detection & Satellite Cloud Masking ☁️🌾

**An AI platform for real-time crop disease detection from RGB images and cloud removal in satellite imagery**, enabling actionable insights for farmers and agritech stakeholders.

> 🌾 One platform → Two key challenges → Smarter AgriTech decisions

---

## 🔑 Key Features

* ⚡ **Hierarchical Disease Detection** – Multi-class classifiers for 100+ disease classes
* ☁️ **Satellite Cloud Masking** – CNN Encoder–Decoder / U-Net for clean imagery
* 🤝 **Scalable & Modular** – Easily extendable pipelines for new crops, diseases, and satellite datasets
* 🕒 **Deployable** – Web API integration with Flask / FastAPI for real-time usage

---

## 📌 Applications

* 🌿 Early crop disease detection from field images
* 🛰️ Cloud removal for satellite imagery to improve crop monitoring
* 📊 Farm-scale insights for yield and disease management
* 🌾 Supports multi-crop, multi-disease pipelines

---

## ⚙️ Methodology

### 1️⃣ Plant Disease Detection (RGB Images)
* **Input:** RGB crop images from fields  
* **Pipeline:** Preprocessing → Hierarchical Multi-Class Classifier → Model Training & Evaluation → API Deployment  
* **Models:** CNNs, Hierarchical Classification, Multi-Label Learning  

**Architecture:**  
RGB Images
│
▼
Preprocessing & Augmentation
│
▼
Hierarchical Classifier
│
▼
Training & Evaluation
│
▼
Deployment via Web API


### 2️⃣ Satellite Cloud Masking
* **Input:** Cloudy satellite images  
* **Pipeline:** Preprocessing → Cloud Masking (U-Net / Encoder–Decoder) → Clean Images  
* **Output:** Cloud-free images for downstream crop analysis  

**Architecture:**  


Cloudy Satellite Images
│
▼
Preprocessing
│
▼
Cloud Masking (U-Net / Encoder–Decoder)
│
▼
Clean Images for Analysis


---

## ✨ Highlights

✔️ Handles **RGB and satellite imagery** in one platform  
✔️ Supports **100+ disease classes**  
✔️ Scalable for new crops and satellite datasets  
✔️ Ready for **real-time deployment**  

---

## 🛠️ Tech Stack

* **ML/DL:** PyTorch, TensorFlow, OpenCV  
* **Models:** CNNs, U-Net, Encoder–Decoder, Hierarchical Classifiers  
* **Data Handling:** Pandas, NumPy  
* **Web Integration:** Flask, FastAPI  

---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/yourusername/cropgen.git  

# Install dependencies
pip install -r requirements.txt  

# Run demo
python app.py

🔮 Future Work

🌿 Add more crop and disease classes

🛰️ Extend cloud masking for multi-spectral satellite images

📈 Integrate predictive analytics for early warning systems
