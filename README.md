# SwinSegFormer: Advancing Aerial Image Semantic Segmentation for Flood Detection

## Abstract
Semantic segmentation of aerial images is vital for unmanned aerial vehicle applications, such as land cover mapping, surveillance, and identifying flood-affected areas for effective natural disaster management and flood impact mitigation. Traditional CNN-based techniques face challenges in capturing global semantic information due to their limited receptive fields and, existing transformer-based architectures often require high computational resources or produce single-scale, low-resolution features, which impairs segmentation performance. To address these limitations, we propose a novel transformer- based model named SwinSegFormer, which leverages the strengths of SegFormer with a lightweight MLP decoder to overcome computational overhead and Swin Transformer (SwinT) with a hierarchical encoder to generate multi-scale resolution features. Our model is trained on the FloodNet dataset and benchmark evaluations, focusing on challenging classes such as vehicles, pools, and flooded and non-flooded roads, which are crucial for effective disaster management. Additionally, we developed a post-processing module to categorize predicted masks into flooded and non-flooded areas based on the affected area. We further validate the performance of our model by making inferences over a small, unlabeled dataset of real-world flood images, potentially enabling its use in first aid activities during floods. The proposed model achieved notable results with a validation mIoU of 75.1%, mDice of 85.4%, and mAcc of 87.1%, representing a 10- 12% improvement compared to vision transformer-based SOTA methods. Future work includes exploring SwinSegFormer’s interpretability and real-time deployment in diverse aerial imagery conditions.

![image](https://github.com/user-attachments/assets/793a84cc-0236-45e0-9590-7ae5036f6c16)

**Published Paper:** [IEEE Xplore](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10979465)

---

## 🔥 SwinSegFormer Model and Supported Models
This repository contains the **SwinSegFormer** model along with other supported models, their predicted results, and corresponding configuration files.

### 📊 Dataset

**FloodNet Dataset:** [Download from Kaggle](https://kaggle.com/datasets/c46b2c738b08fcb6a494f66c17572c9844936498062f7b1884ad8d4c0bbad349)

---

## Citation
@article{shaheen2025swinsegformer,
  title={SwinSegFormer: Advancing Aerial Image Semantic Segmentation for Flood Detection},
  author={Shaheen, Muhammad Tariq and Iqbal, Hafsa and Khurshid, Numan and Sadia, Haleema and Saeed, Nasir},
  journal={IEEE Open Journal of the Computer Society},
  number={01},
  pages={1--12},
  year={2025},
  publisher={IEEE Computer Society}
}

🚀 **Happy Coding!** 🚀
