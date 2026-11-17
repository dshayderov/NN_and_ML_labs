---
license: cc-by-sa-4.0
task_categories:
- image-classification
- image-feature-extraction
- tabular-classification
- feature-extraction
language:
- ar
- en
pretty_name: 'HDL: Hand-drawn Digital Logic Gates Dataset'
---

📌 Dataset Summary

HDL (Hand-drawn Digital Logic Gates) is the first balanced image and tabular dataset dedicated to the classification of hand-drawn digital logic gates. The dataset is designed primarily for machine learning education, computer vision research, and AI-assisted electronics applications.

HDL contains 1,200 hand-drawn images covering the 8 fundamental digital logic gates (AND, OR, NOT (INVERTER), BUFFER, NAND, NOR, XOR, and XNOR), with 150 images per class, ensuring perfect class balance.

🧠 Motivation

Most existing handwritten or hand-drawn datasets focus on:

* Digits (e.g., MNIST) 
* Characters and scripts

However, no publicly available balanced dataset existed for hand-drawn digital logic gates, despite their importance in:

* Digital electronics education
* Circuit analysis
* AI-assisted schematic interpretation

HDL was created to fill this gap and to support:

* Teaching Machine Learning to engineering students
* No-code ML experimentation
* Benchmarking shallow and deep learning models

📂 Images Dataset Structure

```
HDL/
├── AND/
├── OR/
├── NOT/
├── BUFFER/
├── NAND/
├── NOR/
├── XOR/
└── XNOR/
```

* Image format: `.jpg` / `.jpeg`
* Image source: Hand-drawn on paper and photographed or scanned
* Contributors: Umm Al-Qura University students + logic gates drawn using Logisim-evolution

📊 Benchmark Results

The dataset has been extensively benchmarked using both no-code tools and deep learning models.

🔹 Best Result

* Model: EfficientNet with data augmentation
* Platform: Liner.ai
* Accuracy: 92.5%
* F1-score: 92.5%


🔹 Feature Extraction (Image Embedding) (Tabular Dataset)

Image embeddings were generated using:

* SqueezeNet
* Inception v3
* Google ViT
* Facebook DINOv2
* Nvidia MambaVision

Top-performing classifiers:

* Logistic Regression
* Neural Networks

🧪 Typical Use Cases

HDL is suitable for:

🎓 Machine Learning Education
🧠 TinyML & Edge AI
✍️ OCR-like systems for circuit digitization
🧩 Logic gate classification
🖼️ Image embedding & feature extraction experiments
🛠️ No-code ML platforms (Orange Data Mining, Liner.ai)

📄 Research Paper: Bati, Ghassan F. (2026) "HDL: A Balanced Dataset for Hand-Drawn Digital Logic Gates," Journal of King Abdulaziz University: Computing and Information Technology Sciences: Vol. 15: Iss. 1, Article 3.
DOI: https://doi.org/10.64064/1658-6336.1021
https://kauj.researchcommons.org/jcits/vol15/iss1/3
Please cite the dataset if used in academic work.