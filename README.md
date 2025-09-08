# lemon-yolo-classification
# Lemon-YOLO Benchmarking

This repository contains code, datasets, and experimental results for benchmarking multiple YOLO architectures on lemon fruit detection under real-world agricultural conditions. It demonstrates reproducible evaluation protocols, model comparison, and deployment strategies.

---

## 📑 Abstract
This study presents a comprehensive benchmarking framework evaluating seven You Only Look Once (YOLO) architectures—**YOLOv5nu, YOLOv8n, YOLOv11n, YOLOv11s, YOLOv11m, YOLOv11l, and YOLOv12n**—under unified training and evaluation protocols, demonstrating neural network applications through an agricultural computer vision case study.  

The benchmarking methodology employs standardized hyperparameters, data augmentation strategies, and consistent evaluation metrics across all models, ensuring reproducible performance comparisons.  

Using **lemon fruit detection** as a challenging real-world scenario, we evaluated **2,431 augmented images** containing **4,234 annotated instances** under variable illumination, occlusion, and maturity conditions.  

Performance assessment encompassed:
- **Detection accuracy:** Precision, Recall, mAP@0.5, and mAP@0.5–0.95  
- **Computational efficiency:** Frames per second (FPS)  
- **Deployment feasibility:** Model parameters and memory footprint  

Key results:
- **YOLOv11l** achieved the highest accuracy (**0.886 mAP@0.5**)  
- **YOLOv8n** delivered optimal real-time performance (**79.8 FPS**)  

Practical deployment was validated through a **web-based inference interface** and **edge device compatibility analysis**, bridging benchmarking research with operational implementation.  

The framework reveals critical **accuracy–efficiency trade-offs**:  
- Larger models excel in precision-critical applications  
- Lightweight models enable real-time edge deployment  

This benchmarking study provides actionable model selection guidelines, demonstrates neural network deployment in agricultural environments, and establishes a reproducible methodology transferable to broader computer vision domains.  

**Keywords:** YOLO architectures, object detection benchmarking, deep learning, computer vision, real-time inference, neural networks
