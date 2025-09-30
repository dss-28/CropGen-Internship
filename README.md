# 🌱 CropGen - ML for Plant Disease Detection & Satellite Cloud Masking ☁️🌾  

CropGen is an AI platform that tackles **two key AgriTech challenges**:  

1. 🌾 **Plant Disease Detection** from RGB field images  
2. ☁️ **Cloud Masking** for satellite imagery  

---

## 1️⃣ Plant Disease Detection (RGB Images)  

**Objective:** Detect crop diseases early to reduce losses.  

**Approach:**  
- Hierarchical multi-class classification (**100+ disease classes**)  
- Input: RGB crop images from field  
- Models: CNNs, hierarchical classifiers, multi-label learning  
- Integration: Web API via Flask/FastAPI  

**Impact:**  
- ✅ Achieved **baseline-beating accuracy**  
- ✅ Built **scalable pipelines** for new crops and diseases  

**Architecture (Conceptual):**  

RGB Crop Images
│
├─> Data Preprocessing
│
├─> Hierarchical Multi-Class Classifier
│
├─> Model Training & Evaluation
│
└─> Deployment via Web API


---

## 2️⃣ Satellite Cloud Masking  

**Objective:** Remove clouds from satellite images to improve downstream crop monitoring.  

**Approach:**  
- CNN Encoder–Decoder & U-Net architectures  
- Input: Cloudy satellite images  
- Output: Cloud-free imagery ready for analysis  
- Integration: Feeds into crop monitoring and disease detection pipelines  

**Impact:**  
- ✅ Improved satellite image quality and usability  
- ✅ Enabled more accurate crop and yield monitoring  

**Architecture (Conceptual):**  


Cloudy Satellite Images
│
├─> Data Preprocessing
│
├─> Cloud Masking (U-Net / Encoder–Decoder)
│
└─> Clean Images for Downstream Analysis


---

## ⚙️ Tech Stack  

- **ML/DL:** PyTorch, TensorFlow, OpenCV  
- **Models:** CNNs, U-Net, Encoder–Decoder, Hierarchical Classification  
- **Data Handling:** Pandas, NumPy  
- **Web Integration:** Flask, FastAPI  

---

## 🚀 How to Run (Optional)  
```bash
# Clone the repository
git clone https://github.com/yourusername/cropgen.git  

# Install dependencies
pip install -r requirements.txt  

# Run demo
python app.py  
