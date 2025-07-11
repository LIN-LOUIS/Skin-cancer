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

| Paper | Year | Task | Method | Highlights | Link |
|-------|------|------|--------|------------|------|
| **DSCIMABNet** | 2025 | Classification | Multimodal + Attention | Best AUC on ISIC2019 | 🔗 [PDF](#) |
| **SSL-SEFP** | 2025 | Classification | Patch-level SSL | High sensitivity on eyelid melanoma | 🔗 [PDF](#) |
| **SkinFormer** | 2024 | Segmentation | Swin-UNet variant | Top-ranked on ISIC2020 | 🔗 [PDF](#) |
| **M3Former** | 2025 | Multimodal | Clinical + image | Robustness across datasets | 🔗 [PDF](#) |
| **DeBoNet** | 2024 | Classification | Bone suppression ensemble | Enhances TB and lesion detection | 🔗 [PDF](#) |

> 📑 Complete table available at: [Google Sheet](#)

---

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
