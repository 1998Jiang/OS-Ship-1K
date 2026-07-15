# OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection

## 📢 News

Our paper **“OS-Ship-1K: A Pseudo-Paired Optical--SAR Dataset for Multimodal Ship Detection”** has been accepted by the **9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV 2026)**.

---

## 📖 Abstract

Optical--synthetic aperture radar (SAR) remote sensing data can combine the fine-grained representation ability of optical images with the all-day and all-weather observation advantages of SAR images, 
thereby providing complementary information for ship detection. However, publicly available optical--SAR paired ship detection data remain scarce.  
To alleviate this problem, this paper proposes OS-Ship-1K, a pseudo-paired optical--SAR dataset for multimodal ship detection. 
Specifically, we first compare several mainstream unpaired image translation models 
and select CycleGAN to translate optical ship images into SAR-style images. 
Then, spatially aligned pseudo-paired samples are generated through semi-supervised iterative annotation and mapping. 
OS-Ship-1K contains 1,000 pairs of optical and SAR-style images and provides annotations for \textit{Ship} and \textit{Ships}, 
covering sparse offshore, dense offshore, and nearshore scenarios. 
In addition, we evaluate 14 single-modal detectors and 6 multimodal fusion detectors on OS-Ship-1K, 
establishing detection baselines. The dataset are available at \url{https://github.com/1998Jiang/OS-Ship-1K}.

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
