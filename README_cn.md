---
# 📄 README_cn.md
```markdown
# 红外遥感多场景数据集
## 📖 简介
本数据集包含 **融合遥感数据与物理建模的多目标动态红外遥感数据**，总大小约 **150 GB**，主要应用于： 
- 动态场景下飞机/舰船目标的检测与跟踪

每个场景以 `.rar` 压缩包形式存放，便于下载和管理。  
数据集已在 [Zenodo](https://zenodo.org/uploads/17075534)[百度网盘]()长期归档，并提供 DOI 供引用。
---
## 📂 数据内容
数据集结构如下：
Dataset/
│
├── Scene1_Shanghai.rar # 中国上海，覆盖云、城市、海洋场景
├── Scene2_Taiwan.rar # 中国台湾东部，覆盖海洋、云、草地场景
├── Scene3_Western China.rar # 中国西部区域，覆盖森林、草地、雪山场景
└── Scene4_Persian Gulf.rar # 波斯湾区域，覆盖海洋、沙漠、城市场景

- **文件格式**：16-bit TIFF 图像序列
- **时间分辨率**：0.2 秒/帧  
- **空间范围**：约 100 km × 100 km  
- **附加信息**：附带元数据表格（包含目标位置、类别、飞行方向、速度等）

---

## 🔗 下载方式
完整数据集可在Zenodo或百度网盘下载：  
- Zenodo
- 百度网盘
- 每个 `.rar` 文件可单独下载。  

示例下载命令（Linux/macOS）：
```bash
wget https://zenodo.org/record/xxxxx/files/Scene01_Aircraft.rar
wget https://zenodo.org/record/xxxxx/files/Scene02_Ship.rar

## 📑 引用
如果您使用了本数据集，请引用：

📬 联系方式
作者：周晓萱 (中国科学院上海技术物理研究所)
邮箱：zhouxiaoxuan@mail.sitp.ac.cn
