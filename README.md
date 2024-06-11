# Breast Cancer Detection Using Zero-Shot Learning

## Abstract
The rapid advancement of artificial intelligence (AI) and machine learning (ML) has significantly enhanced the capabilities of image classification across various domains, including medical imaging. However, traditional supervised learning models face critical challenges, particularly in medical imaging, due to the dependency on large labeled datasets, which are often difficult, expensive, and time-consuming to obtain. This thesis explores the application of inductive Zero-Shot Learning (ZSL) to address these limitations, specifically focusing on the classification of breast tumors using the BreakHis dataset.

## Methodology
Zero-Shot Learning (ZSL) enables models to recognize and classify unseen classes by leveraging auxiliary information such as semantic embeddings, without requiring labeled examples of those classes during training. This research proposes a modified inductive ZSL model tailored to the BreakHis dataset, which contains histopathological images of breast tumors categorized into eight distinct classes. The model employs a ResNet50 architecture for feature extraction and utilizes Word2Vec for generating semantic embeddings of class labels. A Logistic Regression classifier is trained on the features of seen classes and their corresponding semantic embeddings, enabling the model to generalize to unseen classes during inference.

## Results
The proposed approach demonstrates the potential of ZSL in medical imaging, achieving reasonable accuracy in classifying unseen tumor classes into benign and malignant categories. Despite computational constraints, the study suggests that with advanced resources, further improvements could be achieved through deeper neural networks, more sophisticated embeddings, and advanced optimization techniques.

## Repository Contents
- **Thesis Document**: [Master Thesis. Kamal Hamad.docx](docs/Master%20Thesis.%20Kamal%20Hamad.docx)
- **Code and Scripts**: Relevant code and scripts used in this project.
- **Datasets**: Links or references to the BreakHis dataset used in the study.

## How to Cite
Hamad, K. S. H. (2024). Breast Cancer Detection Using Zero-Shot Learning. Master’s thesis, University of Europe for Applied Sciences.

## Contact
For any questions or collaborations, please contact Kamal Siddig Hussain Hamad at [your-email@example.com].
