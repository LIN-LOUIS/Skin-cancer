# Skin Cancer Research: A Deep Survey (Keep Updating)

<div align="center">


[![](https://img.shields.io/github/stars/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  
[![](https://img.shields.io/github/issues/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  
[![](https://img.shields.io/github/license/yourname/Skin-Cancer-Survey)](https://github.com/yourname/Skin-Cancer-Survey)  

</div>

---

<div align="center">
  <img src="data/HAM10000.png" width="80%">
</div>

<div align="center">
  <sub>上图展示了 HAM10000 数据集中皮肤病变图像的部分示例，包括良性痣与恶性黑色素瘤等多种类型。</sub>
</div>

---

📧 联系邮箱：**lzy13764449097@gmail.com**

---


## 简介（Introduction）

本项目整理并持续更新皮肤癌研究中具有代表性的**深度学习方法、数据集、代码与论文资源**，特别关注 2024–2025 年度的新进展，包括：

- Transformer 与 Diffusion 模型在医学图像中的应用
- 多模态融合（图像 + 临床/文本/基因组）
- 自监督学习与跨模态诊断
- 精准分类、分割与检测任务

希望为皮肤癌影像学研究人员提供一个高效检索与参考的开源平台。如有补充建议，欢迎联系邮箱📮：**lzy13764449097@gmail.com**



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


## 📊 常用皮肤癌数据集总览（2024）

| Dataset Name     | Publication Year | Task Type                  | Modality     | Number of Images                            | Image Format     | Link |
|------------------|------------------|----------------------------|--------------|----------------------------------------------|------------------|------|
| ISIC 2016        | 2016             | Classification, Segmentation | Dermoscopy   | 900 training, 379 testing                    | jpeg, png        | [Link](https://challenge.isic-archive.com/data/#2016) |
| ISIC 2017        | 2017             | Classification, Segmentation | Dermoscopy   | 2000 training, 150 validation, 600 testing   | jpeg, png        | [Link](https://challenge.isic-archive.com/data/#2017) |
| ISIC 2018        | 2018             | Classification, Segmentation | Dermoscopy   | 2594 (segmentation), 10,015 (classification) | jpeg, png        | [Link](https://challenge.isic-archive.com/data/#2018) |
| ISIC 2019        | 2019             | Classification              | Dermoscopy   | 25,331 training                              | jpeg             | [Link](https://challenge.isic-archive.com/data/#2019) |
| ISIC 2020        | 2020             | Classification              | Dermoscopy   | 33,126 training, 10,982 testing              | jpeg             | [Link](https://challenge.isic-archive.com/data/#2020) |
| ISIC 2024        | 2024             | Classification              | Photograph   | 401,059                                      | jpg              | [Link](https://challenge2024.isic-archive.com/) |
| BCN20000         | 2019             | Classification              | Dermoscopy   | 12,413 training, 6,533 testing               | jpg              | [Link](https://figshare.com/articles/journal_contribution/BCN20000_Dermoscopic_Lesions_in_the_Wild/24140028/1) |
| HAM10000         | 2018             | Classification              | Dermoscopy   | 10,015                                       | jpeg             | [Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) |
| PH2              | 2018             | Segmentation                | Dermoscopy   | 200                                          | png              | [Link](https://www.fc.up.pt/addi/ph2%20database.html) |
| MED-NODE         | 2015             | Classification              | Dermoscopy   | 170                                          | jpeg             | [Link](https://www.cs.rug.nl/~imaging/databases/melanoma_naevi/) |
| DERM7PT          | 2018             | Classification              | Dermoscopy   | 2,000                                        | jpg              | [Link](https://derm.cs.sfu.ca/Welcome.html) |
| PAD-UFES-20      | 2020             | Classification              | Photograph   | 2,298                                        | png              | [Link](https://data.mendeley.com/datasets/zr7vgbcyr2/1) |
| Fitzpatrick17    | 2022             | Classification              | Dermoscopy   | 16,577                                       | jpg              | [Link](https://github.com/mattgroh/fitzpatrick17k) |
| MRA-MIDAS        | 2024             | Classification              | Photograph   | 2,919                                        | jpeg, jpg        | [Link](https://aimi.stanford.edu/datasets/mra-midas-Multimodal-Image-Dataset-for-AI-based-Skin-Cancer) |
| SkinCancer       | 2022             | Classification              | Pathology    | 129,364 (29,419 skin cancer-related)         | jpg              | [Link](https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2022.1022967/full) |
| SKINL2           | 2019             | Classification              | Dermoscopy   | 330                                          | png              | [Link](https://www.it.pt/AutomaticPage?id=3459) |



---

## 🌀 Diffusion Models in Skin Imaging
## Segmentation Models
| Model Name                                   | Used Data                        | Dice    | Jaccard | Accuracy |
|----------------------------------------------|----------------------------------|---------|---------|----------|
| Transformer-based U-Net with inter-scale context fusion | ISIC 2017, ISIC 2018            | 0.9257  | -       | 0.9698   |
| Improved U-shaped network                    | ISIC 2017                        | 0.9384  | 0.9679  | 0.9662   |
| Robust optimization of SegNet                | ISIC 2016, ISIC 2017             | 0.925   | 0.875   | -        |
| SegNet for melanoma lesion segmentation      | ISIC 2016, ISIC 2017             | -       | -       | 0.89     |
| YOLO-v8                                      | PH2, ISIC 2017                   | -       | -       | 0.9867   |
| nSknRSUNet                                    | MoleMap, HAM10000                | 0.9413  | -       | 0.9806   |

## Classification and Detection Models
| Model Name                                | Used Data                                     | Accuracy | F1 Score | Sensitivity | Specificity |
|-------------------------------------------|-----------------------------------------------|----------|----------|-------------|-------------|
| SkinFLNet                                  | Clinical images (Taiwan hospitals)            | 0.85     | 0.82     | 0.82        | 0.93        |
| ResNet-50-based DCNN                       | HAM10000                                      | 0.8487   | 0.85     | -           | -           |
| Inception-ResNet-based DCNN                | ISIC 2018–2020                                | 0.97     | 0.97     | 0.99        | 0.93        |
| XAI                                         | Not specified                                 | -        | -        | -           | -           |
| NASNet deep features                       | ISIC 2020                                     | 0.97     | -        | -           | -           |
| NASNet transfer model                      | HAM10000                                      | 0.9985   | -        | -           | -           |
| EfficientNetB0 + K-means                   | Kaggle                                        | 0.87     | -        | -           | -           |
| EfficientNet (fuzzy ensemble)              | ISIC                                          | 0.8815   | -        | -           | -           |
| Optimized MobileNet                        | Not specified                                 | -        | -        | -           | -           |
| U-Net + MobileNet-V3                       | HAM10000                                      | 0.9886   | -        | 0.9635      | 0.9732      |
| Deep CNN for pathologist-level classification | HAM10000, ISIC 2017, PAD-UFES-20           | 0.96     | 0.97     | 0.99        | 0.93        |
| Optimized CNN                              | HAM10000                                      | 0.9778   | -        | -           | -           |
| Modified falcon finch CNN                  | HAM10000                                      | 0.9652   | -        | 0.9669      | 0.9654      |

## Transformer and Multimodal Models
| Model Name                        | Used Data                              | Specialty                                  |
|----------------------------------|----------------------------------------|--------------------------------------------|
| SkinDistilViT                    | ISIC 2019                              | Knowledge distillation                     |
| Soft-attention-based multimodal | Derm7pt                                | Soft attention module                      |
| SkinViT                          | ISIC 2019                              | Outlooker + Transformer blocks             |
| Vision transformer               | HAM10000                               | Self-attention mechanism                   |
| Vision transformers + XAI        | HAM10000                               | Explainable decision process               |
| MONET                            | 105,550 paired images                  | Conceptual annotation (image+text)         |
| Mixed multimodal                 | Not specified                          | Genomic + imaging + clinical integration   |
| SkinGPT-4                        | 52,929 paired images and notes         | LLM-based multimodal diagnosis assistant   |
| Reinforcement learning model     | HAM10000                               | Q-learning + MCTS for optimization         |
## Segmentation + Classification + Transformer/Multimodal
| Model Name                                | Model Type        | Used Data                                     | Accuracy | Dice    | Jaccard | F1 Score | Sensitivity | Specificity | Specialty / Notes                             |
|-------------------------------------------|-------------------|-----------------------------------------------|----------|---------|---------|----------|-------------|-------------|-----------------------------------------------|
| Transformer-based U-Net                   | Segmentation      | ISIC 2017, ISIC 2018                           | 0.9698   | 0.9257  | -       | -        | -           | -           | Inter-scale context fusion                    |
| Improved U-shaped network                 | Segmentation      | ISIC 2017                                     | 0.9662   | 0.9384  | 0.9679  | -        | -           | -           | Multiscale + residual                         |
| Robust optimization of SegNet             | Segmentation      | ISIC 2016, ISIC 2017                           | -        | 0.925   | 0.875   | -        | -           | -           | Bayesian optimization                         |
| SegNet for melanoma                       | Segmentation      | ISIC 2016, ISIC 2017                           | 0.89     | -       | -       | -        | -           | -           | Clinical deployability                        |
| YOLO-v8                                   | Segmentation      | PH2, ISIC 2017                                 | 0.9867   | -       | -       | -        | -           | -           | Real-time detection                           |
| nSknRSUNet                                 | Segmentation      | MoleMap, HAM10000                              | 0.9806   | 0.9413  | -       | -        | -           | -           | U-Net + DeepLab + residual                    |
| SkinFLNet                                  | Classification    | Taiwan clinical images                         | 0.85     | -       | -       | 0.82     | 0.82        | 0.93        | Inception + ResNet fusion                     |
| ResNet-50-based DCNN                       | Classification    | HAM10000                                       | 0.8487   | -       | -       | 0.85     | -           | -           | Feature extraction backbone                   |
| Inception-ResNet-based DCNN                | Classification    | ISIC 2018–2020                                 | 0.97     | -       | -       | 0.97     | 0.99        | 0.93        | Multiscale + residual                         |
| XAI                                         | Classification    | Not specified                                  | -        | -       | -       | -        | -           | -           | Text and region-based explanation             |
| NASNet deep features                       | Classification    | ISIC 2020                                      | 0.97     | -       | -       | -        | -           | -           | Transfer learning                             |
| NASNet transfer model                      | Classification    | HAM10000                                       | 0.9985   | -       | -       | -        | -           | -           | Optimized architecture                        |
| EfficientNetB0 + K-means                   | Classification    | Kaggle skin datasets                           | 0.87     | -       | -       | -        | -           | -           | Clustering enhanced features                  |
| EfficientNet (fuzzy ensemble)              | Classification    | ISIC                                           | 0.8815   | -       | -       | -        | -           | -           | Choquet fuzzy + macro F1 reward               |
| Optimized MobileNet                        | Classification    | Not specified                                  | -        | -       | -       | -        | -           | -           | Pruned + quantized                            |
| Hybrid U-Net + MobileNet-V3                | Classification    | HAM10000                                       | 0.9886   | -       | -       | -        | 0.9635      | 0.9732      | Fusion + Bayesian hyperparam optimization     |
| Pathologist-level Deep CNN                 | Classification    | HAM10000, ISIC 2017, PAD-UFES-20               | 0.96     | -       | -       | 0.97     | 0.99        | 0.93        | On H&E-stained images                         |
| Optimized CNN                              | Classification    | HAM10000                                       | 0.9778   | -       | -       | -        | -           | -           | Data augmentation                             |
| Falcon Finch CNN                           | Classification    | HAM10000                                       | 0.9652   | -       | -       | -        | 0.9669      | 0.9654      | Inspired by nature optimization               |
| SkinDistilViT                              | Transformer       | ISIC 2019                                      | -        | -       | -       | -        | -           | -           | Knowledge distillation from ViT               |
| Soft-attention multimodal                  | Multimodal        | Derm7pt                                        | 0.8304   | -       | -       | -        | -           | Soft attention + trichotomous fusion          |
| SkinViT                                     | Transformer       | ISIC 2019                                      | 0.9109   | -       | -       | -        | -           | Outlooker + transformer + MLP head            |
| Vision Transformer                         | Transformer       | HAM10000                                       | 0.9615   | 0.9814  | 0.9601  | -        | -           | Segment Anything + ViT                        |
| ViT + XAI                                   | Transformer       | HAM10000                                       | -        | -       | -       | -        | -           | Grad-CAM + interpretability                   |
| MONET                                       | Multimodal        | 105,550 paired images                          | -        | -       | -       | -        | -           | Image-text concept matching                   |
| Mixed multimodal                           | Multimodal        | Not specified                                  | -        | -       | -       | -        | -           | Omics + imaging + clinical                    |
| SkinGPT-4                                   | Multimodal        | 52,929 images with text                        | -        | -       | -       | -        | -           | GPT-4 + ViT + report generation               |
| Reinforcement learning model               | RL-based          | HAM10000                                       | -        | -       | -       | -        | -           | Q-learning + Monte Carlo tree search          |

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
