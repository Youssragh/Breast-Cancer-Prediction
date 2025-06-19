# Breast-Cancer-Prediction
**Breast Cancer Prediction — Problem Overview**

This project addresses a binary classification task aimed at predicting whether a breast tumor is malignant (cancerous) or benign (non-cancerous) based on a set of features extracted from digitized medical images.

**Dataset Description**

The dataset utilized in this study originates from fine needle aspirate (FNA) procedures of breast masses. It includes features computed from digitized images of breast cell nuclei and is widely known as the Wisconsin Breast Cancer Diagnostic (WBCD) dataset.

Each instance in the dataset consists of the following:

ID Number: A unique identifier for each patient sample.

Diagnosis: The target variable indicating the class label:

'M': Malignant

'B': Benign

Feature Set: Ten real-valued attributes calculated for each nucleus, describing specific morphological characteristics. These features are:

| Feature               | Description                                                             |
| --------------------- | ----------------------------------------------------------------------- |
| **Radius**            | Mean distance from the nucleus center to its perimeter                  |
| **Texture**           | Standard deviation of grayscale values (image smoothness)               |
| **Perimeter**         | Length of the boundary around the nucleus                               |
| **Area**              | Size of the nucleus region                                              |
| **Smoothness**        | Measure of local variations in the radius lengths                       |
| **Compactness**       | $(\text{Perimeter}^2 / \text{Area}) - 1.0$, indicating boundary density |
| **Concavity**         | Severity of concave portions in the nucleus contour                     |
| **Concave Points**    | Count of concave regions on the nucleus boundary                        |
| **Symmetry**          | Degree of symmetry in the shape of the nucleus                          |
| **Fractal Dimension** | Measurement of contour complexity based on fractal geometry             |


**Objective**
The primary objective is to develop a predictive machine learning model capable of accurately classifying breast tumors based on these features. Such a model can serve as a decision-support tool to assist healthcare professionals in early detection and diagnosis of breast cancer.

**Use Case**
The predictive model trained on this dataset can be integrated into diagnostic software to:

Support radiologists in screening programs.

Reduce the rate of false positives and negatives.

Improve diagnostic efficiency using computational analysis.
