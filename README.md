# Brain-Tumour-Classification
This project presents a deep learning approach for classifying **brain tumours** into their respective types using MRI scans. A modified **Inception V3** model combined with a custom DNN classifier is used to extract and interpret critical visual features for accurate diagnosis.

---

## Overview

The model is trained to classify brain tumours into distinct types, aiding early detection and treatment planning. It uses transfer learning to adapt the Inception V3 architecture for the medical imaging domain.

Tumour types include:
- Meningioma
- Glioma
- Pituitary tumour

---

## Dataset

We use the open-access dataset provided by Cheng et al. [Explore The Dataset](https://doi.org/10.6084/m9.figshare.1512427.v5)


---

##  Model Architecture

- **Backbone:** Pre-trained **Inception V3**
- **Classifier:** Custom **DNN** layers added for fine-tuned classification
- **Training:** Transfer learning with selective layer unfreezing

---

## How to Use
### 01. Open in Colab: Click the button below to launch the notebook in Google Colab:

### 02. Run All Cells: Follow the cells step-by-step. All dependencies are automatically installed, and the code is fully compatible with Colab.

### 03. Adjust File Paths: Update file paths in code cells accordingly.

## Reference

The work was presented on International Conference on Artificial Intelligence for Smart Community, [Read the paper](https://link.springer.com/chapter/10.1007/978-981-16-2183-3_87)
