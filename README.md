# Missile Parts Segmentation and Measurement (Computer Vision Model)

This repository contains a computer vision system developed during an internship project at **DRDO, Pune**. Focused on **segmenting missile parts** and **extracting dimensional measurements** from high-resolution images using deep learning and classical image processing.

## 🧠 Overview

The goal of this system is to:
- **Segment missile components** (e.g., nose, fins, body, tail) from full missile images using instance segmentation.
- **Accurately measure** part dimensions using edge-based post-processing techniques.

The model is built using **Detectron2's Mask R-CNN**, and post-processing is performed using **Canny edge detection** and **Convex Hull** algorithms to estimate part dimensions in pixel space.

---

## 🗂️ Repository Structure

```
missile-parts-segmentation-and-measurement-Computer-Vision-Model/
├── configs/
│   └── config.yaml                  # Detectron2 segmentation model configuration
├── notebooks/
│   └── computer_vision.ipynb        # Full pipeline including segmentation & measurements
├── samples/                         # Example output: Only segmentation output is displayed,
|                                                     for measurements output please visit notebooks/computer_vision.ipynb
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
```


## 🏛️ Acknowledgements

This project was developed as part of an internship at:

**Armament Research & Development Establishment (ARDE), DRDO – Pune, India**

Supervised by research and engineering teams at DRDO.

---
