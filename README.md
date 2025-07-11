# Skin-cancer
# Skin Cancer Research: A Deep Survey (Keep Updating)

<div align="center">

[![](https://img.shields.io/github/stars/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  
[![](https://img.shields.io/github/issues/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  
[![](https://img.shields.io/github/license/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  

</div>

<div align="center">
  <img src="https://www.cdc.gov/cancer/skin/images/social-media/CDC_124732_720px.jpg" width="70%">
</div>

---

## 🌞 Introduction

This repository presents a curated collection of representative **papers**, **datasets**, **methods**, and **codes** on **skin cancer classification, segmentation, and detection** using deep learning, particularly focused on the latest progress in 2024–2025.

We aim to **continuously update** this resource to help researchers navigate through new trends like **transformer-based models**, **diffusion models**, and **multi-modal fusion**.

For collaboration or suggestions, feel free to contact us!

---

## 🧠 Method Taxonomy

### 🎯 Based on Task Type
- **Classification**: Lesion classification (e.g., melanoma vs benign)
- **Segmentation**: Precise boundary delineation of lesions
- **Detection**: Localizing skin cancer regions on dermoscopic/clinical/WSI images
- **Multi-modal Fusion**: Combining image + clinical/meta/genomic data

### 🧪 Based on Model Type
- **CNN-based**: ResNet, DenseNet, MobileNet, EfficientNet
- **Transformer-based**: Swin-T, MedFormer, DS-Former
- **Diffusion-based**: BS-Diff, LeFusion
- **Multimodal Fusion**: Vision + Metadata (e.g., M3Former, MetaNet)
- **Self-Supervised**: SimCLR, SSL-SEFP, BYOL
- **GANs / Adversarial**
- **Ensemble / Voting models**

---

## 📚 Representative Papers (2024–2025)

| Title | Task | Method | Venue | Dataset | Link |
|-------|------|--------|-------|---------|------|
| A Unified Multimodal Foundation Model for Patch-WSI Histopathology | 分类 | CPath-Omni | CVPR | Patch级数据集和WSI级数据集 | [Search](https://scholar.google.com/scholar?q=A+Unified+Multimodal+Foundation+Model+for+Patch-WSI+Histopathology) |
| On the Out-Of-Distribution Generalization of Large Multimodal Models | 其他 | GPT-4V / Gemini 泛化评估 | CVPR | 合成 CMNIST, RMNIST 等 | [Search](https://scholar.google.com/scholar?q=On+the+Out-Of-Distribution+Generalization+of+Large+Multimodal+Models) |
| Multi-faceted Hierarchical Graph-based GNN for Spatial Transcriptomics | 其他 | MERGE 图神经网络 | CVPR | Her2ST, SCC | [Search](https://scholar.google.com/scholar?q=Multi-faceted+Hierarchical+Graph-based+GNN+for+Spatial+Transcriptomics) |
| Interactive Medical Image Analysis with Concept Reasoning | 其他 | CSR（Concept-based Similarity Reasoning） | CVPR | TBX11K, VinDr-CXR, ISIC | [Search](https://scholar.google.com/scholar?q=Interactive+Medical+Image+Analysis+with+Concept+Reasoning) |
| Minding Fuzzy Regions: A Data-driven Alternative to EM in Segmentation | 分割 | DALE | CVPR | ISIC-2016, PH2 | [Search](https://scholar.google.com/scholar?q=Minding+Fuzzy+Regions:+A+Data-driven+Alternative+to+EM+in+Medical+Segmentation) |
| Interactive Medical Image Segmentation Benchmark (IMed-361M) | 分割 | IMIS Baseline | CVPR | IMed-361M | [Search](https://scholar.google.com/scholar?q=Interactive+Medical+Image+Segmentation:+A+Benchmark+Dataset) |
| DSCIMABNet: Deep Skin Cancer Multimodal Attention-Based Net | 检测 | DSCIMABNet + 集成学习 | PR | ISIC 2018, Mendeley | [Search](https://scholar.google.com/scholar?q=DSCIMABNet:+A+novel+multi-head+attention+depthwise+network+for+skin+cancer+diagnosis) |
| kMaXU: Medical Image Segmentation with k-means Mask | 分割 | CNN + Transformer + k-means | PR | ISIC 2018, Mendeley | [Search](https://scholar.google.com/scholar?q=kMaXU:+Medical+image+segmentation+U-Net+with+k-means+mask) |
| DAUD: Domain Adaptation for Unsupervised Skin Cancer Detection | 检测 | 自编码器 + 随机潜变量 | MICCAI | ISIC 2018, Mendeley | [Search](https://scholar.google.com/scholar?q=Domain+Adaptation+for+Unsupervised+Cancer+Detection+in+Skin+Images) |
| SkinCON: Towards Consensus for Uncertainty in Diagnosis | 其他 | DRAPS + 不确定性量化 | MICCAI | SkinCON (ISIC 2019 扩展) | [Search](https://scholar.google.com/scholar?q=SkinCON:+Towards+Consensus+for+the+Uncertainty+Estimation+in+Skin+Diagnosis) |
| Lesion-Aware GAN for Skin Cancer Augmentation | 生成 | 对抗式生成 | WACV | ISIC, PH2 | [Search](https://scholar.google.com/scholar?q=Lesion-Aware+GAN+for+Skin+Cancer+Augmentation) |
| Few-shot Meta Segmentation for Skin Cancer | 分割 | 原型网络 + 领域自适应 | PR | ISIC 2016–2020 | [Search](https://scholar.google.com/scholar?q=Few-shot+Meta+Segmentation+for+Skin+Cancer) |
| Uncertainty-guided Semi-supervised Segmentation | 分割 | U-SAM + 蒸馏机制 | TMI | ISIC 2018 | [Search](https://scholar.google.com/scholar?q=Uncertainty-guided+Self-training+for+Semi-supervised+Skin+Cancer+Segmentation) |
| SSL-SEFP: Self-supervised Patch Fusion for Eyelid Melanoma | 分类 | Patch融合 + 多尺度对比学习 | JBHI | ZJU-2, PatchCamelyon | [Search](https://scholar.google.com/scholar?q=SSL-SEFP:+Self-supervised+Fusion+Patch+Learning+for+Eyelid+Melanoma) |
| Multiscale Fusion Transformer for Lesion Classification | 分类 | Transformer + 多尺度融合 | TMI | ISIC 2019 | [Search](https://scholar.google.com/scholar?q=Multiscale+Fusion+Transformer+for+Lesion+Classification+in+Skin+Cancer) |


## 🧬 Skin Cancer Datasets

| Dataset | Resolution | Task | Classes | Public | Link |
|---------|------------|------|---------|--------|------|
| ISIC 2016–2020 | Varies | Class / Seg / Detect | ~7 | ✅ | [ISIC Archive](https://www.isic-archive.com) |
| HAM10000 | 600×450 | Classification | 7 | ✅ | [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) |
| PAD-UFES-20 | Varies | Class / Meta | 6 | ✅ | [Kaggle](https://www.kaggle.com/andrewmvd/ufes-skin-lesion) |
| Derm7pt | 1024×768 | Multimodal | 8 + Metadata | ✅ | [Official Website](https://www.derm7pt.org) |
| PH2 | 768×560 | Segmentation | 2 | ✅ | [PH2 Dataset](https://www.fc.up.pt/addi/ph2%20database.html) |
| ISIC 2024 Challenge | Varies | Multitask | TBD | ✅ | [Challenge Website](https://challenge.isic-archive.com) |

---

## 🌀 Diffusion Models in Skin Imaging

| Model | Task | Highlights | Link |
|-------|------|------------|------|
| **BS-LDM (JBHI 2025)** | Bone suppression | High-res latent conditional model | [PDF](https://openreview.net/forum?id=3b9SKkRAKw) |
| **BS-Diff (ISBI 2024)** | Bone suppression | Conditional diffusion, CXR | [PDF](https://openreview.net/forum?id=3b9SKkRAKw) |
| **LeFusion** | Lesion synthesis | Disease-focused region control | [Code](https://github.com/M3DV/LeFusion) |

---

## 🎯 Application Scenarios

- Skin lesion classification
- Lesion boundary segmentation
- Multi-modal diagnosis (image + metadata)
- Rare lesion synthesis
- Early screening and triage
- Clinical explainability & uncertainty estimation

---

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourname/Skin-Cancer-Survey&type=Timeline)](https://star-history.com/#yourname/Skin-Cancer-Survey&Timeline)

---

## 🧾 Citation

### BS-LDM (JBHI 2025)
```bibtex
@article{sun2025bs,
  title={BS-LDM: Effective Bone Suppression in High-Resolution Chest X-Ray Images with Conditional Latent Diffusion Models},
  author={Sun, Yifei and Chen, Zhanghao and others},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2025}
}
