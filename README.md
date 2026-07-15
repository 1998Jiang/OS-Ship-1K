# OS-Ship-1K

## 📢 News

Our paper **“OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection”** has been accepted by the **9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV 2026)**.

---

## 📖 Paper Introduction

Optical and synthetic aperture radar (SAR) images provide complementary information for ship detection. However, publicly available spatially aligned optical--SAR ship detection datasets remain scarce.

To address this issue, we construct **OS-Ship-1K**, a pseudo-paired optical--SAR dataset for multimodal ship detection. Several unpaired image translation methods are compared, and CycleGAN is selected to generate SAR-style images from optical images. Spatially aligned pseudo-paired samples are then obtained through semi-supervised iterative annotation and mapping.

---

## 🗂️ Dataset

OS-Ship-1K contains:

- 1,000 pairs of spatially aligned optical and SAR-style images;
- annotations for two categories: `Ship` and `Ships`;
- three types of scenes: sparse offshore, dense offshore, and nearshore;
- benchmarks based on 14 single-modality detectors and 6 multimodal fusion detectors.

The dataset supports both single-modality ship detection and multimodal fusion detection.

---

## 📥 Download

The OS-Ship-1K dataset can be downloaded from Baidu Netdisk.

```text
Baidu Netdisk:
TODO: Add the download link

Extraction Code:
TODO: Add the extraction code
```

---

## 📚 Citation

If OS-Ship-1K is useful for your research, please cite our paper:

```bibtex
@inproceedings{jiang2026osship1k,
  title     = {OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection},
  author    = {Jiang, Lingjie and Luo, Xin and Lin, Yuhao and Peng, Dongliang and Xu, Kaiyuan},
  booktitle = {Proceedings of the 9th Chinese Conference on Pattern Recognition and Computer Vision},
  year      = {2026}
}
```

The citation information will be updated after the official Springer proceedings and DOI become available.

---

## 📮 Contact

For questions about the dataset or paper, please contact:

- **Lingjie Jiang**  
  Email: [13586245162@163.com](mailto:13586245162@163.com)

- **Dongliang Peng**  
  Email: [dlpeng@hdu.edu.cn](mailto:dlpeng@hdu.edu.cn)

You can also submit questions through the repository's [Issues](https://github.com/1998Jiang/OS-Ship-1K/issues) page.
