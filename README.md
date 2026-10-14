# Microplastic-Detection — GangaDrishthi

Website for **"Development of a Real-Time Multi-Modal Sensor for Field-Based Microplastic Detection"** (project **GangaDrishthi**) — presented at the IEEE 2nd International Conference on Cognitive Computing in Engineering, Communications, Sciences and Biomedical Health Informatics (IC3ECSBHI), February 12–14, 2026.

**Live site:** https://microplastic.vatsalyaaa.me
**Paper (ResearchGate):** https://www.researchgate.net/publication/403861770_Development_of_a_Real-Time_Multi_Modal_Sensor_for_Field_Based_Microplastic_Detection

## About the project

A compact, low-cost system that fuses three sensing modalities for rapid, on-site microplastic quantification in water:

- **Multispectral optical imaging** (400–940 nm programmable LED array)
- **Impedance spectroscopy** (1 kHz – 2 MHz microfluidic electrodes)
- **YOLOv8 deep-learning microscopy** (CSPDarkNet53 backbone, anchor-free heads)

A Fully Connected Fusion Network with scaled dot-product attention combines the modalities to classify polymer type (PET, PP, PE, PS, PVC), estimate particle size, and produce a **Microplastic Risk Index (MRI)**. An 8-bit quantized TFLite model runs on the ESP32-S3 at <200 ms per sample, with geo-tagged results synced to a companion app for contamination heatmaps.

## Authors

Gautam Buddha University, Greater Noida, India

- Vatsalya Bhadaurya — Computer Science & Engineering
- Shashwat Upadhayay — Computer Science & Engineering
- Vinayak Dwivedi — Electronics & Communication Engineering
- Yuvraj Singh — Computer Science & Engineering
- Yaduraj Singh — Computer Science & Engineering
- Sharmishtha — Computer Science & Engineering
