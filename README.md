# Adapting Mask R-CNN for instance segmentation of submarine dunes on bathymetric digital models (DBMs)

This repository contains the code and configurations used for the **instance segmentation of underwater dunes** from **Digital Bathymetric Models (DBMs)** using a **customized Mask R-CNN** model.  
This work was developed as part of a Master's thesis in Geomatics at Université Laval.

## 🧠 Key Features

- ✅ Integration of **CIoU** loss for bounding box regression.
- ✅ Use of **DIoU** for improved Non-Maximum Suppression (NMS).
- ✅ Addition of **Edge Agreement Head** to refine mask boundaries.
- ✅ Evaluation of **ResNet-50** and **ResNet-101** as backbones.
- ✅ Experiments with **frozen**, **partially unfrozen**, and **fully unfrozen** backbones.
- ✅ Ablation studies with and without **Feature Pyramid Networks (FPN)**.
- ✅ Impact analysis of **data augmentation** strategies on training/validation.

## 👩‍💻 Author

Nada Bouferdous
Master’s student in Geomatics
Université Laval, Canada
Nada Bouferdous | bouferdousnada2@gmail.com

## 📊 Results & Metrics

Evaluation metrics include:
mAP
Precision / Recall
F1-score

Full results and ablation study details are provided in the thesis and related publications.
