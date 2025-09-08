# Multi-Scene Infrared Remote Sensing Dataset

## 📖 Introduction
This dataset contains **multi-scene infrared remote sensing data**, with a total size of about **150 GB**.  
It is mainly designed for:  
- Detection and tracking of aircraft/ship targets in dynamic scenes  

Each scene is stored in a `.rar` archive for easy download and management.  
The dataset has been permanently archived on [Zenodo](https://zenodo.org/uploads/17075534) and [BaiduNetdisk](), and is assigned a DOI for citation.  

---

## 📂 Dataset Contents
The dataset consists of the following scenes:
Dataset/
│
├── Scene01_Aircraft.rar # Shanghai, China: includes cloud, urban, and ocean scenes
├── Scene02_Ship.rar # Eastern Taiwan, China: includes ocean, cloud, and grassland scenes
├── Scene03_Cloud.rar # Western China: includes forest, grassland, and snow mountain scenes
└── Scene04_Persian Gulf.rar # Persian Gulf region: includes ocean, desert, and urban scenes

- **File format**: 16-bit TIFF image sequences  
- **Temporal resolution**: 0.2 s/frame  
- **Spatial coverage**: ~100 km × 100 km  
- **Additional information**: Includes metadata tables (containing target position, category, flight direction, speed, etc.)  

---

## 🔗 Download
The complete dataset can be downloaded from **Zenodo** or **Baidu Cloud**:  

- DOI: [10.5281/zenodo.17075534]( )  
- Each `.rar` file can be downloaded individually.  

Example commands (Linux/macOS):
```bash
wget https://zenodo.org/record/xxxxx/files/Scene01_Aircraft.rar
wget https://zenodo.org/record/xxxxx/files/Scene02_Ship.rar
```
---
## 📑 Citation
- If you use this dataset, please cite:

---
## 📬 Contact
