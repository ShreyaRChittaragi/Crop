# 🌿 Crop and Weed Detection using YOLOv5

An AI-powered precision agriculture solution to detect and classify **crops and weeds** using **YOLOv5**, with simulated pesticide spraying only on weeds. This project is implemented in **Google Colab**, optimized for **GPU**, and trained on a custom YOLO-labeled dataset.

---

## 👤 Student Details

- **Name:** Shreya R Chittaragi  
- **Email:** shreyarchittaragi24@gmail.com  
- **Domain:** AI & ML Engineering  
- **Institute:** JNNCE, Shivamogga  
- **Internship Provider:** Edunet Foundation

---

## 📌 Project Title

**Crop and Weed Detection using YOLOv5**

---

## 🧠 Abstract

This project presents an AI-driven approach to detect and distinguish between **crops and weeds** using the YOLOv5 object detection framework. The objective is to simulate **precision spraying** of pesticides only on weeds, thereby reducing chemical usage and minimizing crop contamination.

We used a custom dataset with YOLO-formatted annotations, enhanced via data augmentation. The YOLOv5 model was trained and evaluated using Google Colab, with outputs including bounding boxes, class-wise visualizations, and a simulated spraying mechanism.

---

## 🎯 Project Objectives

- Build an object detection model to identify **crops** and **weeds**
- Train an accurate and lightweight YOLOv5 model
- Simulate **targeted spraying** on detected weeds only

---

## 🧪 Methodology

1. Collected and cleaned real-world agricultural image data.
2. Resized high-res images to `512x512` resolution.
3. Applied data augmentation using `Keras ImageDataGenerator`.
4. Annotated images using YOLO format manually.
5. Trained a YOLOv5 model in Google Colab (GPU-accelerated).
6. Visualized predictions: bounding boxes + class distribution charts.
7. Added simulation logic for spraying pesticide on weeds only.

---

## 📊 Results & Visualizations

- ✅ Successful object detection for two classes: **crop** and **weed**
- 🔲 Bounding boxes with confidence scores
- 📈 Pie chart and bar graph showing weed/crop distribution
- 🚿 Spray simulation (weeds-only)
- 📄 Summary table saved as CSV
- 🖼️ All prediction results were reviewed visually inside Colab

---

## 🧰 Tools & Technologies

- `Python`, `OpenCV`, `Matplotlib`, `Pandas`
- `Google Colab` (GPU - Tesla T4)
- `YOLOv5` by Ultralytics
- `Keras` (for augmentation)
- `LabelImg` (for manual annotations)
- `GitHub` (version control and repo management)

---

## ✅ Conclusion

This project proves that **deep learning + computer vision** can enhance agricultural practices by reducing pesticide usage and protecting crops. With further integration into **drones or robots**, this solution has real-world potential for **automated smart farming**.

---

## 🔮 Future Enhancements

- Live detection using a webcam or drone feed
- Mobile/web dashboard for farmers
- Migrate to YOLOv8 for improved performance
- Add support for soil/plant health analytics

---

## 🔗 GitHub Repository

👉 [View Project on GitHub](https://github.com/ShreyaRChittaragi/Crop)

---

> 💡 _Feel free to clone or fork this repo to contribute or experiment with new enhancements!_
