# Multi-Scene Infrared Remote Sensing Dataset

## 📖 Introduction
This dataset contains **A Multi-Target Dynamic Infrared Remote Sensing Dataset Fusing Remote Sensing Data and Physical Modeling*, with a total size of about **150 GB**.  
It is mainly designed for:  
- Detection and tracking of aircraft/ship targets in dynamic scenes  

- Each scene is stored in a `.rar` archive for easy download and management.  
- The dataset has been permanently archived on [Zenodo](https://zenodo.org/uploads/17213990) and [BaiduNetdisk](https://pan.baidu.com/s/11fGqpjKCtvAi3j83nN2hsw) DIRD, and is assigned a DOI for citation.  

---

## 📂 Dataset Contents
The dataset consists of the following scenes:
```bash
Dataset/
│
├── Scene1_Shanghai.rar # Shanghai, China: includes cloud, urban, and ocean scenes
├── Scene2_Taiwan.rar # Eastern Taiwan, China: includes ocean, cloud, and grassland scenes
├── Scene3_Western-China.rar # Western China: includes forest, grassland, and snow mountain scenes
└── Scene4_Persian-Gulf.rar # Persian Gulf region: includes ocean, desert, and urban scenes
```

- **File format**: 16-bit TIFF image sequences  
- **Temporal resolution**: 0.2 s/frame  
- **Spatial coverage**: ~100 km × 100 km  
- **Additional information**: Includes metadata tables (containing target position, category, flight direction, speed, etc.)  

---

## 🔗 Download
The complete dataset can be downloaded from **Zenodo** or **BaiduNetdisk**:  

- Zenodo
- BaiduNetdisk
- Each `.rar` file can be downloaded individually.  

Example commands (Linux/macOS):
```bash
wget https://zenodo.org/record/17213990/files/Scene1_Shanghai.rar
wget https://zenodo.org/record/17213990/files/Scene2_Taiwan.rar
wget https://zenodo.org/record/17213990/files/Scene3_WesternChina.rar
wget https://zenodo.org/record/17213990/files/Scene4_Persian Gulf.rar
```
---
## 📑 Citation
- If you use this dataset, please cite:

---
## 📬 Contact
Author: ZHOU Xiaoxuan (Shanghai Institute of Technical Physics, Chinese Academy of Sciences)
Email: zhouxiaoxuan@mail.sitp.ac.cn
