# Explainable AI for Image Classification Using Integrated Gradients and Grad-CAM

This project explores explainability techniques for deep learning models, particularly **Grad-CAM** and **Integrated Gradients (IG)**, applied to **ResNet-50** and **DenseNet-121**. These methods help visualize the decision-making process of convolutional neural networks (CNNs) in image classification tasks. 

## Project Summary

Deep learning models achieve high accuracy in image classification but are often viewed as "black boxes." This project evaluates how **Grad-CAM** and **IG** explain CNN predictions by highlighting important image regions. The study compares their **interpretability**, **faithfulness**, and **localization accuracy** using quantitative metrics such as **Intersection over Union (IoU), Precision, Recall**, and **Faithfulness Deletion Tests**.

### Key Findings:
- **Grad-CAM** provides better spatial localization of important regions.
- **Integrated Gradients (IG)** offers fine-grained pixel-level attributions but requires post-processing.
- **DenseNet-121** produces more structured and localized explanations compared to **ResNet-50**.
- **TCAV (Concept-Based Explainability)** shows IG aligns better with human-interpretable concepts.

## Files and Structure
- `Gradcam_Densenet.ipynb` → Grad-CAM on DenseNet-121
- `IG_Densenet.ipynb` → Integrated Gradients on DenseNet-121
- `Gradcam_resnet50.ipynb` → Grad-CAM on ResNet-50
- `IG_resnet50.ipynb` → Integrated Gradients on ResNet-50
- `FP_XAI_KontaratouFredjZadoun.pdf` → Full research report with methodology, results, and analysis.

