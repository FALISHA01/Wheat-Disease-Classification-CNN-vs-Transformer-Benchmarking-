# Wheat-Disease-Classification-CNN-vs-Transformer-Benchmarking-

_April 2025 — Deep Learning Project_

This repository presents a comparative study of CNN- and Transformer-based architectures for classifying wheat leaf diseases. The study benchmarks lightweight CNN models (MobileNetV2, EfficientNetB0) against modern Vision Transformer variants (CaiT, Swin Transformer) on a curated wheat disease dataset across five categories.



##  Problem Statement

Early detection of wheat leaf diseases is crucial for minimizing crop loss and improving food security. We designed and tested deep learning pipelines to accurately classify diseases from leaf images, comparing:

- Convolutional Neural Networks (CNNs)
- Vision Transformers (ViTs)



##  Models Compared

| Model Type | Architecture     | Notes                           |
|------------|------------------|---------------------------------|
| CNN        | MobileNetV2      | Lightweight and fast            |
| CNN        | EfficientNetB0   | High accuracy, low params       |
| Transformer| CaiT             | Deeper transformer with class token |
| Transformer| Swin Transformer | Hierarchical vision transformer |



## 🧾 Dataset

-  Custom-curated dataset with **5 wheat disease categories**
-  Public dataset source (optionally) or synthetic augmentations


##  Evaluation

Each model was evaluated using:
-  Accuracy
-  Confusion Matrix
-  Error Heatmaps (Grad-CAM visualizations)




