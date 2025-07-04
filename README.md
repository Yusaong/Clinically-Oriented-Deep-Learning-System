# OERR-Net: Clinically Oriented Deep Learning System Integrating Linear and Morphological Assessment for External Orthodontic Root Resorption

## Introduction

**OERR-Net** is an innovative, clinically oriented deep learning system developed for the objective, real-time linear assessment and 3D visualization of Orthodontic External Root Resorption (OERR) based on Cone-beam Computed Tomography (CBCT) data. By integrating both classic linear measurement techniques and advanced 3D morphological analysis, OERR-Net addresses the limitations of manual assessment and aims to enhance clinical decision-making in orthodontics.

![image-20250704102601635](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20250704102601635.png)

## Key Features

- **Apex-aware Tooth Segmentation**: Employs the Swin-UNETR model to achieve highly accurate 3D tooth segmentation and reconstruction.
- **Automatic Tooth Length Measurement**: Introduces the novel ToothLM algorithm for precise, reproducible, and efficient measurement of tooth length.
- **Severity Grading & 3D Visualization**: Enables simultaneous OERR severity grading and intuitive 3D morphological visualization.
- **End-to-End Validation**: Ensures the reliability of the entire workflow, from segmentation to grading, by minimizing cumulative errors.
- **Superior Performance**: Demonstrates significant improvements in accuracy and reliability compared to traditional methods and manual assessments.

## Results

- **Segmentation Accuracy**: Achieved a Dice Similarity Score of 90.98%.
- **Length Measurement**: Demonstrated excellent agreement with expert measurements (ICC = 0.999).
- **Severity Grading Accuracy**: Achieved 97.37% accuracy for upper incisors and 96.82% for lower incisors.
- **Visualization**: Effectively captures subtle morphological changes, even in cases with indistinct anatomical boundaries.

## Project Status

This project is currently in the introduction and demonstration phase. The source code and detailed usage instructions will be released in future updates!

---