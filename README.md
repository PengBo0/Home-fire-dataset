# Home-fire-dataset

A dataset for indoor home fire detection tasks, designed for training object detection models such as YOLO.

---

## 📂 Dataset Overview

The **Home-fire Dataset** is constructed to support early detection of household fires. It contains **6,500 images** with corresponding annotation files (in YOLO-compatible `.txt` format), covering various indoor fire scenarios.

The dataset is split in a **6:2:2 ratio**:
- `train.zip`: **3,900 images**
- `val.zip`: **1,300 images**
- `test.zip`: **1,300 images**

Each `.zip` archive contains both images and label files, suitable for immediate use in training fire-related object detection models.

---

## 🖼️ Sample Overview

This dataset includes images of **flames** and **smoke** captured:
- under various lighting and environmental conditions,
- from household surveillance footage,
- and during the **early ignition stages** of indoor fires.

Special attention is given to **small-scale flames and early smoke**, which are crucial for timely fire alarm systems.

---

## 📸 Data Collection Process

The dataset was collected from:
- Public platforms: **Pexels**, **Pixabay**, **YouTube**, **BiliBili**
- Private contributions from volunteers

A total of **~400 videos** were reviewed, edited, and converted into static images. All sources used are listed in the file below:

🔗 [Images and video sources used in this dataset](https://github.com/PengBo0/Home-fire-dataset/blob/main/dataPath/dataPath.md)

<div align="center">
  <img src="https://github.com/PengBo0/Home-fire-dataset/blob/main/images/figure1.png" width="400px">
  <img src="https://github.com/PengBo0/Home-fire-dataset/blob/main/images/figure2.png" width="400px">
</div>

---

## 🙏 Acknowledgements

We sincerely thank all creators of the referenced videos and images for their generous contributions.

We also extend our gratitude to the following individuals for participating in the video recording process:
**JianJun Peng, TianXiang Feng, and Liu Chang**.

Their materials and efforts were crucial in constructing this dataset and enabling research in early fire detection.

---

## 📄 License

This dataset is released under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.  
You are free to use it for **non-commercial research and academic purposes** with proper citation.

🔗 License details: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

---
## 📌 Citation

This dataset is part of the following publication.  
**If you use the Home-fire Dataset in your work, please cite this paper:**

```bibtex
@ARTICLE{10985749,
  author={Peng, Bo and Kim, Tae-Kook},
  journal={IEEE Access}, 
  title={YOLO-HF: Early Detection of Home Fires Using YOLO}, 
  year={2025},
  volume={13},
  number={},
  pages={79451-79466},
  keywords={YOLO;Feature extraction;Accuracy;Proposals;Wildfires;Real-time systems;Adaptation models;Lighting;Indoor environment;Convolution;YOLO;object detection;fire dataset;home fire detection;smoke detection},
  doi={10.1109/ACCESS.2025.3566907}
}
