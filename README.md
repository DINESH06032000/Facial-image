# Preserving Data Security in Facial Images Using De-identification

## 📌 Purpose
To develop a technology that enables sharing of video recordings for valuable purposes while ensuring that individuals involved in legal activities remain anonymous. This is achieved by protecting identities captured in public places through facial de-identification.

---

## 📖 Description
This project uses **image averaging techniques** to reduce the granularity of facial data.  
Facial landmark detection is implemented using **dlib**, which provides coordinate mappings for key facial features.  
These coordinates are then used to anonymize or modify identifiable regions of the face.

---

## 🎯 Objectives
1. Develop a **highly secure system** for de-identification of facial features.  
2. Ensure that remaining facial details are **minimally distorted**.  
3. Enable sharing of **only anonymized data**.  
4. Detect and determine **facial landmarks** for the face region.

---

## ⚙️ Functionality
- Extract multiple facial images.  
- Plot facial feature coordinates using landmark detection.  
- Average some or all facial features for de-identification.  
- Modify or distort selected features to preserve user privacy.

---

## 🚀 Performance
- The project code is organized for **maximum efficiency**.  
- Uses the **best available techniques** to enhance performance and output quality.

---

## 💻 Technology Stack
- **Language:** Python  
- **Interface / Environment:** Jupyter Notebook  

---

## 📷 Techniques Used
- Image Preprocessing  
- Facial Landmark Detection (dlib)  
- Facial Averaging  
- Feature Modification for Privacy  

---

## 📝 How to Run
1. Install required Python libraries:
   ```bash
   pip install dlib opencv-python numpy imutils
