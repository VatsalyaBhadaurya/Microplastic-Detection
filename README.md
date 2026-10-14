# Microplastic-Detection — GangaDrishthi

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![IEEE](https://img.shields.io/badge/IEEE-IC3ECSBHI%202026-00629B.svg)](https://ieeexplore.ieee.org/document/11469066)
[![Live site](https://img.shields.io/badge/Live-microplastic.vatsalyaaa.me-1877bf.svg)](https://microplastic.vatsalyaaa.me)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-Contributor%20Covenant-ff69b4.svg)](CODE_OF_CONDUCT.md)

Website for **"Development of a Real-Time Multi-Modal Sensor for Field-Based Microplastic Detection"** (project **GangaDrishthi**) — presented at the IEEE 2nd International Conference on Cognitive Computing in Engineering, Communications, Sciences and Biomedical Health Informatics (IC3ECSBHI), February 12–14, 2026.

- **Live site:** https://microplastic.vatsalyaaa.me
- **Paper (IEEE Xplore):** https://ieeexplore.ieee.org/document/11469066
- **Paper (ResearchGate):** https://www.researchgate.net/publication/403861770_Development_of_a_Real-Time_Multi_Modal_Sensor_for_Field_Based_Microplastic_Detection

## About the project

A compact, low-cost system that fuses three sensing modalities for rapid, on-site microplastic quantification in water:

- **Multispectral optical imaging** (400–940 nm programmable LED array)
- **Impedance spectroscopy** (1 kHz – 2 MHz microfluidic electrodes)
- **YOLOv8 deep-learning microscopy** (CSPDarkNet53 backbone, anchor-free heads)

A Fully Connected Fusion Network with scaled dot-product attention combines the modalities to classify polymer type (PET, PP, PE, PS, PVC), estimate particle size, and produce a **Microplastic Risk Index (MRI)**. An 8-bit quantized TFLite model runs on the ESP32-S3 at <200 ms per sample, with geo-tagged results synced to a companion app for contamination heatmaps.

## Authors

- Vatsalya Bhadaurya — Computer Science & Engineering
- Shashwat Upadhayay — Computer Science & Engineering
- Vinayak Dwivedi — Electronics & Communication Engineering
- Yuvraj Singh — Computer Science & Engineering
- Yaduraj Singh — Computer Science & Engineering
- Sharmishtha — Computer Science & Engineering

## Citation

If you use this work or reference this project, please cite the paper. A machine-readable
[`CITATION.cff`](CITATION.cff) is included — GitHub shows a **"Cite this repository"** button
in the sidebar that generates APA/BibTeX automatically.

```bibtex
@inproceedings{gangadrishthi2026,
  title     = {Development of a Real-Time Multi-Modal Sensor for Field-Based Microplastic Detection},
  author    = {Bhadaurya, Vatsalya and Upadhayay, Shashwat and Dwivedi, Vinayak and Singh, Yuvraj and Singh, Yaduraj and Sharmishtha},
  booktitle = {2026 2nd International Conference on Cognitive Computing in Engineering, Communications, Sciences and Biomedical Health Informatics (IC3ECSBHI)},
  year      = {2026},
  month     = feb,
  publisher = {IEEE},
  isbn      = {979-8-3315-5691-4},
  url       = {https://ieeexplore.ieee.org/document/11469066}
}
```

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) and please follow our
[Code of Conduct](CODE_OF_CONDUCT.md).

## License

The website source code and assets in this repository are released under the
[MIT License](LICENSE).

The research paper itself (included as `paper.pdf`) is © 2026 IEEE and is redistributed for
academic and reference purposes, subject to
[IEEE copyright terms](https://www.ieee.org/publications/rights/index.html).
