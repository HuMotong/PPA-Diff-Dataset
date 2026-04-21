# Full-Stokes Polarization Feature Image Dataset

A representative subset of the full-Stokes polarization feature image dataset used in the paper:

**"Full-Stokes Polarization Feature Image Fusion via Polarization Physics-Aware Diffusion Model"**

This repository provides outdoor scenes captured by our self-developed common-aperture full-Stokes polarimetric camera. Each scene contains four polarization feature maps (S0, DoP, AoP, EoP) stored as float32 NumPy arrays：
- S0: normalized intensity, range [0, 1]
- DoP: degree of polarization, range [0, 1]
- AoP: angle of polarization, range [-90°, 90°] (in degrees)
- EoP: ellipticity angle, range [-45°, 45°] (in degrees)

> **Note:** This is a partial release. The complete dataset will be released after the next-generation imaging platform is finalized.

---

## Data Download

The dataset is hosted on Baidu Netdisk due to file size.

- **Link:** [https://pan.baidu.com/s/XXXXXXXX](https://pan.baidu.com/s/XXXXXXXX)
- **Extraction code:** `XXXX`

File size: approximately XX GB (uncompressed).

---

## References

If you use this dataset in your research, please cite our paper:

```bibtex
@article{ppa_diff_2026,
  title   = {Full-Stokes Polarization Feature Image Fusion via Polarization Physics-Aware Diffusion Model},
  author  = {Hu, Motong and Pan, Yue and Xue, Donglin and Xu, Xiping and Wang, Peiyu},
  journal = {Expert Systems with Applications},
  year    = {2026},
  note    = {manuscript under review}
}

(BibTeX will be updated once the paper is published.)
