# BanglaMM-Disaster: Multimodal Disaster Classification for Bangla Social Media

[![arXiv](https://img.shields.io/badge/arXiv-2511.21364-b31b1b.svg)](https://arxiv.org/abs/2511.21364)
[![Conference](https://img.shields.io/badge/SPICSCON-2025-blue)](https://doi.org/10.48550/arXiv.2511.21364)

This repository contains the research materials for **BanglaMM-Disaster**, a multimodal transformer-based deep learning framework for disaster classification in Bangla, presented at **IEEE SPICSCON 2025**.

## 📄 Paper Information

**Title:** BanglaMM-Disaster: A Multimodal Transformer-Based Deep Learning Framework for Multiclass Disaster Classification in Bangla

**Authors:** Ariful Islam, Md Rifat Hossen, Md. Mahmudul Arif, Abdullah Al Noman, Md Arifur Rahman

**Conference:** 2025 IEEE International Conference on Signal Processing, Information, Communication and Systems (SPICSCON), November 21-22, 2025, University of Rajshahi, Bangladesh

**arXiv:** [2511.21364 [cs.LG]](https://arxiv.org/abs/2511.21364)

## 🔍 Abstract

Natural disasters remain a major challenge for Bangladesh, so real-time monitoring and quick response systems are essential. In this study, we present BanglaMM-Disaster, an end-to-end deep learning-based multimodal framework for disaster classification in Bangla, using both textual and visual data from social media. We constructed a new dataset of **5,037 Bangla social media posts**, each consisting of a caption and a corresponding image, annotated into one of **nine disaster-related categories**.

The proposed model integrates transformer-based text encoders, including **BanglaBERT, mBERT, and XLM-RoBERTa**, with CNN backbones such as **ResNet50, DenseNet169, and MobileNetV2**, to process the two modalities. Using early fusion, the best model achieves **83.76% accuracy**. This surpasses the best text-only baseline by **3.84%** and the image-only baseline by **16.91%**. Our analysis also shows reduced misclassification across all classes, with noticeable improvements for ambiguous examples.

## 🎯 Key Contributions

- **Novel Dataset**: 5,037 Bangla social media posts with paired captions and images across 9 disaster categories
- **Multimodal Framework**: Integration of transformer-based text encoders with CNN-based image encoders
- **Performance**: 83.76% accuracy with early fusion strategy
- **Significant Improvements**: +3.84% over text-only and +16.91% over image-only baselines
- **Real-world Application**: Designed for real-time disaster response in low-resource settings

## 📊 Dataset

The dataset contains **5,037 samples** annotated into **9 disaster classes**:

- Earthquake
- Flood
- Fire
- Landslide
- Cyclone
- Heavy Rainfall
- Storm
- Drought
- Others/Non-disaster

Each sample consists of:

- Bangla text caption (social media post)
- Corresponding image
- Disaster category label

## 🏗️ Model Architecture

### Text Encoders

- BanglaBERT
- mBERT (Multilingual BERT)
- XLM-RoBERTa

### Image Encoders

- ResNet50
- DenseNet169
- MobileNetV2

### Fusion Strategy

- Early fusion approach for combining multimodal features

## 📈 Results

| Model Type            | Accuracy   |
| --------------------- | ---------- |
| Text-only (Best)      | 79.92%     |
| Image-only (Best)     | 66.85%     |
| **Multimodal (Best)** | **83.76%** |

**Improvements:**

- +3.84% over text-only baseline
- +16.91% over image-only baseline

## 📁 Repository Structure

```
BanglaMM-Disaster/
├── paper/                          # Research paper files
│   ├── BanglaMM-Disaster_arxiv.pdf        # arXiv preprint
│   ├── BanglaMM-Disaster_published.pdf    # Published conference version
│   └── BanglaMM-Disaster_manuscript.docx  # Manuscript document
├── presentation/                   # Conference presentation
│   ├── SPICSCON2025_presentation.pptx     # Presentation slides
│   ├── SPICSCON2025_presentation.pdf      # Slides in PDF format
│   └── SPICSCON2025_presentation.mp4      # Presentation video
├── figures/                        # Paper figures and visualizations
│   ├── error_analysis.png                 # Error analysis visualization
│   ├── example_multimodal_sample.png      # Sample data example
│   ├── multimodal_methodology.png         # Methodology diagram
│   ├── multimodal_architecture.png        # Model architecture
│   ├── text_only_results.png              # Text-only model results
│   └── visual_only_results.png            # Visual-only model results
├── supplementary/                  # Additional materials
│   ├── 3MT_presentation.pptx              # Three Minute Thesis slides
│   ├── 3MT_presentation.pdf               # 3MT slides PDF
│   ├── 3MT_presentation_video.mp4         # 3MT video 1
│   └── 3MT_presentation_alternative.mp4   # 3MT video 2
├── copyright-documents/            # Conference registration & copyright
│   ├── conference_paper_submission.pdf
│   ├── copyright_transfer.pdf
│   ├── express_submission.pdf
│   ├── online_registration.docx
│   ├── online_registration.pdf
│   ├── payment_receipt.pdf
│   └── student_registration.pdf
├── README.md                       # This file
└── .gitignore                      # Git ignore file
```

## 📚 Citation

If you use this work in your research, please cite:

```bibtex
@misc{islam2025banglammdisaster,
      title={BanglaMM-Disaster: A Multimodal Transformer-Based Deep Learning Framework for Multiclass Disaster Classification in Bangla},
      author={Ariful Islam and Md Rifat Hossen and Md. Mahmudul Arif and Abdullah Al Noman and Md Arifur Rahman},
      year={2025},
      eprint={2511.21364},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2511.21364}
}
```

## 🔗 Links

- **arXiv Paper:** https://arxiv.org/abs/2511.21364
- **DOI:** https://doi.org/10.48550/arXiv.2511.21364
- **Conference:** IEEE SPICSCON 2025

## 👥 Authors

- **Ariful Islam** - [Contact]
- **Md Rifat Hossen** - [Contact]
- **Md. Mahmudul Arif** - [Contact]
- **Abdullah Al Noman** - [Contact]
- **Md Arifur Rahman** - [Contact]

## 📧 Contact

For questions or collaboration opportunities, please contact [Md Rifat Hossen](mailto:your.email@example.com)

## 📝 License

This work is presented at IEEE SPICSCON 2025. Please refer to the copyright documents for usage rights.

## 🙏 Acknowledgments

Presented at the 2025 IEEE International Conference on Signal Processing, Information, Communication and Systems (SPICSCON), University of Rajshahi, Bangladesh.

---

**Keywords:** Multimodal Learning, Disaster Classification, Bangla NLP, Transformer Models, Social Media Analysis, Low-Resource Languages, Deep Learning, Computer Vision
