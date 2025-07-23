
# TML25_A4_15
# TML ASSIGNMENT 4 
# Explainable AI Methods for Deep Learning Models
**Team:** 15  
**Members:** Hina Lilaram, Javed Akhtar

---

### Overview

This repository contains our solution for Assignment 4 of the Trustworthy Machine Learning course, focused on Explainable AI Methods for Deep Learning Models. The objective is to implement and analyze various explainability techniques to understand how deep learning models make decisions, focusing on visualization methods like grad-cam, LIME and CLIP model dissection to provide insights into model behavior.
---


### Files and Descriptions

- `task_01/TASK1.ipynb`: CLIP model dissection and analysis notebook.
- `task_01/results`: Directory containing analysis results and visualizations
- `task_02/task_02.ipynb`: Implementation of CAM methods (GradCAM, ScoreCAM, AblationCAM)
- `task_02/heatmaps`: Generated visualization heatmaps for task 2.
- `task_03/task_03.ipynb`: Implementation of LIME method.
- `task_03/../heatmaps`: Generated visualization heatmaps for task 3.
- `task_04/task_04.ipynb`: Comparison of results for grad-cam and LIME for task 4.
- `task_04/analysis`: heatmaps comparisons, iou by type boxplot and execution vs fidelity analysis.
- `TML25_A4_15_report.pdf`: This is the report file.

---

## Features

- **Quantitative Metrics:** Entropy, sparsity, and perturbation measures for explanation evaluation.
- **Comparative Analysis:**  Evaluation of explanation quality across different image categories.
- **  Visualization:** Heatmap generation to show model attention regions

---

## Configuration

The implementation includes various configuration options:
- Pre-trained models: ResNet50 for CAM methods, CLIP for model dissection.
- Visualization parameters: Heatmap thresholds and overlay setting
- Analysis metrics: Parameters for entropy calculation and perturbation tests.
- Image categories: Various ImageNet classes for testing explainability across different object types

---

*For any questions or clarifications, please contact either team member.*