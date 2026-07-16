# OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection

## 📢 News

Our paper **“OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection”** has been accepted by the **9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV 2026)**.

---

## 📖 Abstract

Optical--synthetic aperture radar (SAR) remote sensing data can combine the fine-grained representation ability of optical images with the all-day and all-weather observation advantages of SAR images, thereby providing complementary information for ship detection. However, publicly available optical--SAR paired ship detection data remain scarce. To alleviate this problem, this paper proposes OS-Ship-1K, a pseudo-paired optical--SAR dataset for multimodal ship detection. Specifically, we first compare several mainstream unpaired image translation models and select CycleGAN to translate optical ship images into SAR-style images. Then, spatially aligned pseudo-paired samples are generated through semi-supervised iterative annotation and mapping. OS-Ship-1K contains 1,000 pairs of optical and SAR-style images and provides annotations for 'Ship' and 'Ships', covering sparse offshore, dense offshore, and nearshore scenarios. In addition, we evaluate 14 single-modal detectors and 6 multimodal fusion detectors on OS-Ship-1K, establishing detection baselines. The dataset is available at https://github.com/1998Jiang/OS-Ship-1K.

---

## 🗂️ Dataset

OS-Ship-1K contains:

- 1,000 pairs of spatially aligned optical and SAR-style images;
- annotations for two categories: `Ship` and `Ships`;
- benchmarks based on 14 single-modality detectors and 6 multimodal fusion detectors.

The dataset supports both single-modality ship detection and multimodal fusion detection.
<img width="2586" height="1917" alt="compare_gan_prcv" src="https://github.com/user-attachments/assets/5e7bc34e-eba6-46f4-8f45-de7efe1f7420" />

---

## 📥 Download

The OS-Ship-1K dataset can be downloaded from Baidu Netdisk.

```text
Baidu Netdisk:
https://pan.baidu.com/s/1x5eGQDsoMFhEPuNoSTYW9A
code: 0869 

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

---

## 📮 Contact

For questions about the dataset or paper, please contact:

- **Lingjie Jiang**  
  Email: [13586245162@163.com](mailto:13586245162@163.com)

You can also submit questions through the repository's [Issues](https://github.com/1998Jiang/OS-Ship-1K/issues) page.
