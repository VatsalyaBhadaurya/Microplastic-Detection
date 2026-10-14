# Microplastic-Detection

Website for **"Development of a Real-Time Multi-Modal Sensor for Field-Based Microplastic Detection"** — presented at the IEEE 2nd International Conference on Cognitive Computing in Engineering, Communications, Sciences and Biomedical Health Informatics (IC3ECSBHI), February 12–14, 2026.

🌐 **Live site:** https://microplastic.vatsalyaaa.me

## About the project

A compact, low-cost system that fuses three sensing modalities for rapid, on-site microplastic quantification in water:

- **Multispectral optical imaging** (400–940 nm programmable LED array)
- **Impedance spectroscopy** (1 kHz – 2 MHz microfluidic electrodes)
- **YOLOv8 deep-learning microscopy** (CSPDarkNet53 backbone, anchor-free heads)

A Fully Connected Fusion Network with scaled dot-product attention combines the modalities to classify polymer type (PET, PP, PE, PS, PVC), estimate particle size, and produce a **Microplastic Risk Index (MRI)**. An 8-bit quantized TFLite model runs on the ESP32-S3 at <200 ms per sample, with geo-tagged results synced to a companion app for contamination heatmaps.

## Authors

Gautam Buddha University, Greater Noida, India

- Shashwat Upadhayay — Computer Science & Engineering
- Vinayak Dwivedi — Electronics & Communication Engineering
- Vatsalya Bhadaurya — Computer Science & Engineering
- Yuvraj Singh — Computer Science & Engineering
- Yaduraj Singh — Computer Science & Engineering
- Sharmishtha — Computer Science & Engineering

## Tech

Static site — plain HTML, CSS, and vanilla JavaScript. No build step. The full research paper is embedded and downloadable (`paper.pdf`).

## Local preview

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Hosted on **GitHub Pages** with a custom domain (`microplastic.vatsalyaaa.me`) configured via a Cloudflare CNAME record. The `CNAME` file in the repo root sets the custom domain; enable Pages from the `main` branch in the repository settings.
