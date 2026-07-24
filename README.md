# Awesome Look-Up Tables

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Update](https://img.shields.io/github/last-commit/whut09/Awesome-Look-Up-Tables)
![Papers](https://img.shields.io/badge/papers-31-blue)

A curated list of research papers whose central method is a look-up table
(LUT). The collection covers image enhancement, restoration, super-resolution,
fusion, style transfer, model quantization, efficient inference, and related
learning tasks.

The venues are listed in the requested order. “ICML” is used for the requested
“lcml”. See the [search methodology](docs/search-methodology.md) for coverage,
inclusion rules, and excluded material.

## Table of Contents

- [CVPR](#cvpr)
- [ICCV](#iccv)
- [ECCV](#eccv)
- [NeurIPS](#neurips)
- [ICLR](#iclr)
- [ICML](#icml)
- [IJCV](#ijcv)
- [TPAMI](#tpami)
- [Contributing](#contributing)
- [License](#license)

## Paper List

<!-- PAPER_TABLES:START -->

### CVPR

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2026 | CVPR | **ShiftLUT: Spatial Shift Enhanced Look-Up Tables for Efficient Image Restoration** | [[paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zeng_ShiftLUT_Spatial_Shift_Enhanced_Look-Up_Tables_for_Efficient_Image_Restoration_CVPR_2026_paper.html)] [[code](https://github.com/Sailor-t/ShiftLUT)] | Image restoration |
| 2026 | CVPR | **Memory Matters: Boosting Training-Free Zero-Shot Temporal Action Localization with a Learnable Lookup Table** | [[paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_Memory_Matters_Boosting_Training-Free_Zero-Shot_Temporal_Action_Localization_with_a_CVPR_2026_paper.html)] | Temporal action localization |
| 2025 | CVPR | **DnLUT: Ultra-Efficient Color Image Denoising via Channel-Aware Lookup Tables** | [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Yang_DnLUT_Ultra-Efficient_Color_Image_Denoising_via_Channel-Aware_Lookup_Tables_CVPR_2025_paper.html)] [[code](https://github.com/Stephen0808/DnLUT)] | Image denoising |
| 2025 | CVPR | **AutoLUT: LUT-Based Image Super-Resolution with Automatic Sampling and Adaptive Residual Learning** | [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Xu_AutoLUT_LUT-Based_Image_Super-Resolution_with_Automatic_Sampling_and_Adaptive_Residual_CVPR_2025_paper.html)] [[code](https://github.com/SuperKenVery/AutoLUT)] | Image super-resolution |
| 2024 | CVPR | **Look-Up Table Compression for Efficient Image Restoration** | [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Look-Up_Table_Compression_for_Efficient_Image_Restoration_CVPR_2024_paper.html)] [[code](https://github.com/leenas233/DFC)] | Image restoration |
| 2022 | CVPR | **AdaInt: Learning Adaptive Intervals for 3D Lookup Tables on Real-Time Image Enhancement** | [[paper](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_AdaInt_Learning_Adaptive_Intervals_for_3D_Lookup_Tables_on_Real-Time_CVPR_2022_paper.html)] [[code](https://github.com/ImCharlesY/AdaInt)] | Image enhancement |
| 2022 | CVPR | **Learnable Lookup Table for Neural Network Quantization** | [[paper](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Learnable_Lookup_Table_for_Neural_Network_Quantization_CVPR_2022_paper.html)] | Model quantization |
| 2021 | CVPR | **Practical Single-Image Super-Resolution Using Look-Up Table** | [[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Jo_Practical_Single-Image_Super-Resolution_Using_Look-Up_Table_CVPR_2021_paper.html)] [[code](https://github.com/yhjo09/SR-LUT)] | Image super-resolution |

### ICCV

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2025 | ICCV | **SA-LUT: Spatial Adaptive 4D Look-Up Table for Photorealistic Style Transfer** | [[paper](https://openaccess.thecvf.com/content/ICCV2025/html/Gong_SA-LUT_Spatial_Adaptive_4D_Look-Up_Table_for_Photorealistic_Style_Transfer_ICCV_2025_paper.html)] | Style transfer |
| 2025 | ICCV | **Lightweight and Fast Real-Time Image Enhancement via Decomposition of the Spatial-Aware Lookup Tables** | [[paper](https://openaccess.thecvf.com/content/ICCV2025/html/Kim_Lightweight_and_Fast_Real-time_Image_Enhancement_via_Decomposition_of_the_ICCV_2025_paper.html)] | Image enhancement |
| 2025 | ICCV | **IM-LUT: Interpolation Mixing Look-Up Tables for Image Super-Resolution** | [[paper](https://openaccess.thecvf.com/content/ICCV2025/html/Park_IM-LUT_Interpolation_Mixing_Look-Up_Tables_for_Image_Super-Resolution_ICCV_2025_paper.html)] | Image super-resolution |
| 2025 | ICCV | **Video Color Grading via Look-Up Table Generation** | [[paper](https://openaccess.thecvf.com/content/ICCV2025/html/Shin_Video_Color_Grading_via_Look-Up_Table_Generation_ICCV_2025_paper.html)] | Video color grading |
| 2025 | ICCV | **LUT-Fuse: Towards Extremely Fast Infrared and Visible Image Fusion via Distillation to Learnable Look-Up Tables** | [[paper](https://openaccess.thecvf.com/content/ICCV2025/html/Yi_LUT-Fuse_Towards_Extremely_Fast_Infrared_and_Visible_Image_Fusion_via_ICCV_2025_paper.html)] [[code](https://github.com/zyb5/LUT-Fuse)] | Image fusion |
| 2023 | ICCV | **MEFLUT: Unsupervised 1D Lookup Tables for Multi-Exposure Image Fusion** | [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Jiang_MEFLUT_Unsupervised_1D_Lookup_Tables_for_Multi-exposure_Image_Fusion_ICCV_2023_paper.html)] [[code](https://github.com/Hedlen/MEFLUT)] | Image fusion |
| 2023 | ICCV | **Reconstructed Convolution Module Based Look-Up Tables for Efficient Image Super-Resolution** | [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Liu_Reconstructed_Convolution_Module_Based_Look-Up_Tables_for_Efficient_Image_Super-Resolution_ICCV_2023_paper.html)] | Image super-resolution |
| 2021 | ICCV | **Real-Time Image Enhancer via Learnable Spatial-Aware 3D Lookup Tables** | [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Real-Time_Image_Enhancer_via_Learnable_Spatial-Aware_3D_Lookup_Tables_ICCV_2021_paper.html)] | Image enhancement |

### ECCV

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2024 | ECCV | **Image-Adaptive 3D Lookup Tables for Real-Time Image Enhancement with Bilateral Grids** | [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/6517_ECCV_2024_paper.php)] | Image enhancement |
| 2024 | ECCV | **Taming Lookup Tables for Efficient Image Retouching** | [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7541_ECCV_2024_paper.php)] [[code](https://github.com/Stephen0808/ICELUT)] | Image retouching |
| 2024 | ECCV | **Online Video Quality Enhancement with Spatial-Temporal Look-Up Tables** | [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/9175_ECCV_2024_paper.php)] | Video enhancement |
| 2022 | ECCV | **Learning Series-Parallel Lookup Tables for Efficient Image Super-Resolution** | [[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6698_ECCV_2022_paper.php)] [[code](https://github.com/zhjy2016/SPLUT)] | Image super-resolution |
| 2022 | ECCV | **SepLUT: Separable Image-Adaptive Lookup Tables for Real-Time Image Enhancement** | [[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1740_ECCV_2022_paper.php)] [[code](https://github.com/ImCharlesY/SepLUT)] | Image enhancement |
| 2022 | ECCV | **MuLUT: Cooperating Multiple Look-Up Tables for Efficient Image Super-Resolution** | [[paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1756_ECCV_2022_paper.php)] [[code](https://github.com/ddlee-cn/MuLUT)] | Image super-resolution |

### NeurIPS

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2025 | NeurIPS | **Pan-LUT: Efficient Pan-Sharpening via Learnable Look-Up Tables** | [[paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/b7e80990ff6268f8572eab63b7b7da05-Abstract-Conference.html)] | Pan-sharpening |
| 2024 | NeurIPS | **TinyLUT: Tiny Look-Up Table for Efficient Image Restoration at the Edge** | [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/9b01c4a7d3fc49875dad3c13848bcd9e-Abstract-Conference.html)] [[code](https://github.com/Jonas-KD/TinyLUT)] | Image restoration |
| 2023 | NeurIPS | **Lookup Table Meets Local Laplacian Filter: Pyramid Reconstruction Network for Tone Mapping** | [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/b3a08d179347e33414badadf100e4e8d-Abstract-Conference.html)] | Tone mapping |

### ICLR

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2024 | ICLR | **LUT-GEMM: Quantized Matrix Multiplication Based on LUTs for Efficient Inference in Large-Scale Generative Language Models** | [[paper](https://openreview.net/forum?id=gLARhFLE0F)] [[code](https://github.com/naver-aics/lut-gemm)] | Efficient LLM inference |

### ICML

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2024 | ICML | **Privacy-Preserving Embedding via Look-Up Table Evaluation with Fully Homomorphic Encryption** | [[paper](https://proceedings.mlr.press/v235/kim24ab.html)] | Privacy-preserving ML |

### IJCV

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2025 | IJCV | **Learning Extensible Series-Parallel Lookup Tables for Efficient Image Super-Resolution** | [[paper](https://doi.org/10.1007/s11263-025-02516-1)] | Image super-resolution |

### TPAMI

| Year | Pub | Title | Links | Topic |
|:---:|:---:|:---|:---:|:---:|
| 2026 | TPAMI | **Deep Lookup Network** | [[paper](https://doi.org/10.1109/TPAMI.2025.3605660)] | Efficient vision inference |
| 2024 | TPAMI | **Toward DNN of LUTs: Learning Efficient Image Restoration with Multiple Look-Up Tables** | [[paper](https://doi.org/10.1109/TPAMI.2024.3401048)] [[code](https://github.com/ddlee-cn/MuLUT)] | Image restoration |
| 2022 | TPAMI | **Learning Image-Adaptive 3D Lookup Tables for High Performance Photo Enhancement in Real-Time** | [[paper](https://doi.org/10.1109/TPAMI.2020.3026740)] [[code](https://github.com/HuiZeng/Image-Adaptive-3DLUT)] | Image enhancement |

<!-- PAPER_TABLES:END -->

## Contributing

Contributions are welcome. Please:

1. Add only papers whose central contribution is LUT-based.
2. Use the paper's final publication year and an official proceedings or DOI link.
3. Add an official code link when one is publicly available.
4. Keep the venue order used in this README and update `data/papers.json`.

## License

Released under the [MIT License](LICENSE).
