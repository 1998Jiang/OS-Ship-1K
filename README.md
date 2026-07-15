# OS-Ship-1K

[![Conference](https://img.shields.io/badge/PRCV-2026-blue.svg)](https://github.com/1998Jiang/OS-Ship-1K)
[![Dataset](https://img.shields.io/badge/Dataset-OS--Ship--1K-green.svg)](https://github.com/1998Jiang/OS-Ship-1K)
[![License](https://img.shields.io/badge/License-Research%20Use-lightgrey.svg)](LICENSE)

Official repository of the paper:

> **OS-Ship-1K: A Pseudo-Paired Optical–SAR Dataset for Multimodal Ship Detection**

The paper has been accepted by the **9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV 2026)**.

---

## Introduction

Optical and synthetic aperture radar (SAR) remote sensing images provide complementary information for ship detection. Optical imagery offers fine-grained visual representations, while SAR imagery provides all-day and all-weather observation capabilities. However, publicly available spatially aligned optical–SAR ship detection datasets remain limited.

To alleviate this problem, we construct **OS-Ship-1K**, a pseudo-paired optical–SAR dataset for multimodal ship detection. We first compare several mainstream unpaired image-to-image translation methods and select CycleGAN to translate optical ship images into SAR-style images. Spatially aligned pseudo-paired samples are subsequently generated through semi-supervised iterative annotation and mapping.

OS-Ship-1K contains:

- **1,000 pairs** of spatially aligned optical and SAR-style images;
- annotations for two categories: `Ship` and `Ships`;
- three representative scenarios:
  - sparse offshore scenes;
  - dense offshore scenes;
  - nearshore scenes;
- benchmarks based on **14 single-modality detectors** and **6 multimodal fusion detectors**.

The dataset can support research on single-modality ship detection, multimodal fusion detection, optical–SAR image translation, and cross-modal remote sensing image analysis.

---

## Dataset Overview

<p align="center">
  <img src="https://github.com/user-attachments/assets/b7e9287d-d623-4e1f-b22b-dde80ea2cdb3"
       width="850"
       alt="Comparison of unpaired image translation methods">
</p>

<p align="center">
  <em>Comparison of different unpaired image translation methods used in the construction of OS-Ship-1K.</em>
</p>

The optical images are collected from publicly available ship detection datasets. CycleGAN is used to generate corresponding SAR-style images while preserving the spatial layout of ships and background regions. The annotations are refined through a semi-supervised iterative procedure and mapped between the spatially aligned image pairs.

---

## Dataset Download

The OS-Ship-1K dataset can be downloaded from Baidu Netdisk:

- **Baidu Netdisk:** [Download OS-Ship-1K](请在此处填写百度网盘链接)
- **Extraction Code:** `请填写提取码`

Example:

```text
Baidu Netdisk: https://pan.baidu.com/s/xxxxxxxxxxxxxxxx
Extraction Code: xxxx
