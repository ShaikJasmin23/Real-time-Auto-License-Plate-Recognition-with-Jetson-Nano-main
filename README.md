# 🔍 Real-time Auto License Plate Recognition with Jetson Nano 🚗



A real-time automatic license plate recognition (ALPR) system using Jetson Nano, deep learning, and computer vision.

---

## 📸 Demo

![Plate OCR Output](doc/images/plate_result2.gif)

---

## 🚀 Features

- 🎯 Real-time plate detection and OCR
- ⚡ Optimized for NVIDIA Jetson Nano
- 🧠 Pre-trained ONNX models (SSD-Mobilenet)
- 📂 Organized project structure
- ✅ Easy to set up and extend

---

## 📁 Project Structure

```
📦 Real-time-License-Plate-Recognition/
 ┣ 📂 doc/
 ┃ ┣ 📄 dataset.md
 ┃ ┣ 📄 jetson-setup.md
 ┃ ┣ 📄 plate-detect.md
 ┃ ┣ 📄 plate-ocr.md
 ┃ ┗ 📂 images/
 ┣ 📂 networks/
 ┃ ┣ 📂 az_plate/
 ┃ ┗ 📂 az_ocr/
 ┣ 📄 detectnet-camera.py
 ┣ 📄 .vscode/settings.json
 ┗ 📄 README.md
```

---

## 🧰 Requirements

- Python 3.6+
- Jetson Nano (JetPack installed)
- OpenCV
- ONNX Runtime
- NumPy

---

## ⚙️ Setup & Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/ShaikJasmin23/Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano-main.git
cd Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano-main
```

### Step 2: Set Up Jetson Nano

Follow the detailed guide in:
```
doc/jetson-setup.md
```

### Step 3: Run the Detection Script
```bash
python3 detectnet-camera.py
```

---

## 🧠 Models

| Task             | Model File                         | Location               |
|------------------|-------------------------------------|------------------------|
| Plate Detection  | az_plate_ssdmobilenetv1.onnx        | networks/az_plate/     |
| OCR              | az_ocr_ssdmobilenetv1_2.onnx        | networks/az_ocr/       |

> These models are trained and saved in ONNX format.

---

## 📚 Documentation

All help and explanation files are inside the `doc/` folder:

| File              | Purpose                             |
|-------------------|--------------------------------------|
| `dataset.md`      | Dataset preparation steps            |
| `jetson-setup.md` | Jetson Nano software setup           |
| `plate-detect.md` | Plate detection explanation          |
| `plate-ocr.md`    | OCR model usage and logic            |

---

## 👨‍💻 Author

**Shaik Jasmin**  
🔗 [GitHub Profile](https://github.com/ShaikJasmin23)


