# 🌳 Identification of Deforestation Drivers using ResNet50 (Segmentation Model)

This repository presents a deep learning-based segmentation approach to identify the primary drivers of deforestation using satellite imagery. A pretrained ResNet50 backbone powers the segmentation model, fine-tuned to detect and classify deforested regions. The project is developed in Jupyter Notebook, but due to upload limitations, the notebook is shared in HTML format.

---

## 🚀 Overview

- **Objective:** To detect and highlight regions undergoing deforestation and infer potential contributing factors using semantic segmentation.
- **Approach:** Leveraged transfer learning with a ResNet50 encoder in a segmentation network.
- **Development Environment:** Python (Jupyter Notebook)
- **Status:** Core code under restricted access; essential logic shared via HTML.
- **Primary Focus:** Model demonstration, not full code disclosure.

---

## 🧠 Key Features

- Satellite image preprocessing for segmentation.
- ResNet50-based encoder-decoder architecture.
- Deforestation region highlighting via masks.
- Insight generation into potential human/natural drivers.
- Visualization of predictions.

---

## 📂 Repository Structure

📦 Identification-of-Deforestation-Drivers/
├── model_demo.html # HTML export of Jupyter Notebook with training, architecture, and predictions
├── README.md # Project documentation
└── assets/ # (Optional) Satellite input/output image samples


---

## 🧰 Tech Stack

- **Language:** Python 3.8+
- **Libraries:** TensorFlow 2.x, NumPy, Matplotlib, OpenCV, Keras
- **Notebook:** Jupyter (shared as HTML due to GitHub upload constraints)

---

## 📎 Usage Instructions

1. **Download and open** `model_demo.html` in a browser to explore:
   - Model architecture and training strategy
   - Dataset preprocessing pipeline
   - Visual segmentation outputs on sample images

2. **Not Included:**
   - Raw dataset (satellite images and masks)
   - Mask generation and post-processing scripts (withheld for privacy/compliance)
   - Original Jupyter Notebook (.ipynb)

> 🔒 **Note:** Source code for mask generation and utilities is confidential and not publicly released.

---

## 📈 Future Enhancements

- Add explainability (Grad-CAM, SHAP) to interpret prediction regions.
- Expand to multi-class drivers (agriculture, mining, urban expansion).
- Integrate with GIS platforms for large-scale deployment.
- Develop a web-based interface for policy and environmental research access.

---

## 📬 Contact

For academic discussions, collaboration, or access under NDA:

- 📧 Email: sarthakj3214@gmail.com  
- 💻 GitHub: [SarthajNp](https://github.com/SarthajNp)

---

## 📜 License

This repository is for educational and non-commercial research purposes. Code sharing is partially restricted due to data sensitivity and project ethics.

---

*“Forests whisper stories. Our model tries to read them — pixel by pixel, mask by mask.”*
