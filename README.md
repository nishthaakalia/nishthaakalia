<div align="center">

![Nishtha Kalia · BCA, Computer Science and Applications · Chandigarh, India](./assets/header.svg)

![BCA](https://img.shields.io/badge/BCA-Computer%20Science%20%26%20Applications-6495ED?style=for-the-badge&labelColor=3E6FD8)
![MCM DAV College for Women](https://img.shields.io/badge/MCM%20DAV%20College%20for%20Women-Panjab%20University-8FA8F0?style=for-the-badge&labelColor=3E6FD8)
![Chandigarh, India](https://img.shields.io/badge/📍-Chandigarh%2C%20India-BFE3FA?style=for-the-badge&labelColor=6495ED)

</div>

### 🌼 Hello, I'm Nishtha

I'm a BCA student in the Department of Computer Science and Applications at Mehr Chand Mahajan DAV College for Women,
Panjab University, Chandigarh. I'm interested in machine learning that can be trusted: careful data handling,
honest evaluation, calibrated confidence and explanations that are actually checked.

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 🎓 Education

| | |
|---|---|
| **Bachelor of Computer Applications (BCA)** | Department of Computer Science and Applications, Mehr Chand Mahajan DAV College for Women, Panjab University, Chandigarh, India |

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 💙 Featured project

<div align="center">

[![NEURO//SCAN: Brain Tumour MRI Classification with EfficientNet-B0 and explainable AI. v2 test accuracy 91.9%, macro-F1 0.919, four classes, leakage-aware split. Click to open the live demo.](./assets/featured-neuroscan.png)](https://nishthaakalia.github.io/brain-tumor-mri-classification/)

<sub>Click the banner to open the live in-browser demo.</sub>

</div>

**[Brain Tumour MRI Classification: Leakage-Aware, Calibrated and Explainable EfficientNet-B0](https://github.com/nishthaakalia/brain-tumor-mri-classification)**: four-way brain MRI
slice classification (glioma, meningioma, pituitary tumour, no tumour) on the Kaggle Brain Tumor MRI Dataset.

- 🔍 **Leakage-aware split**: a perceptual-hash audit finds near-duplicates shared by the official Training and Testing folders and removes them from training.
- 📈 **v2 results** on the 1,600-image Testing folder: **91.9% accuracy**, **0.919 macro-F1**, **0.987 macro ROC-AUC** (v1: 93.4%; v2 is preferred because its split is cleaner).
- 🌡️ **Calibration**: temperature scaling lowers the expected calibration error from 0.070 to 0.052, with an "uncertain" flag for low-confidence predictions.
- 🧠 **Six sanity-checked explanation methods**: Grad-CAM, Grad-CAM++, Integrated Gradients, occlusion, KernelSHAP and LIME, tested with deletion/insertion faithfulness and a model-randomisation check.
- 🌐 **In-browser demo**: the model runs as ONNX in the browser, so images never leave the device. Research and education only, not a medical device.

<div align="center">

[![Live demo](https://img.shields.io/badge/▶%20Live%20demo-NEURO%2F%2FSCAN-6495ED?style=for-the-badge&logo=githubpages&logoColor=white)](https://nishthaakalia.github.io/brain-tumor-mri-classification/)
[![White paper v2](https://img.shields.io/badge/📄%20White%20paper-v2%20PDF-3E6FD8?style=for-the-badge)](https://github.com/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/paper/brain_tumor_mri_white_paper.pdf)
[![Repository](https://img.shields.io/badge/Repository-brain--tumor--mri--classification-8FA8F0?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nishthaakalia/brain-tumor-mri-classification)
[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-1E3A6E?style=for-the-badge&logo=googlecolab&logoColor=F9AB00)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/01_data_and_deduplication.ipynb)

</div>

<details>
<summary><b>All five Colab notebooks (v2)</b></summary>

| # | Notebook | |
|---|---|---|
| 1 | Data and deduplication | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/01_data_and_deduplication.ipynb) |
| 2 | Training EfficientNet-B0 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/02_training_efficientnet_b0.ipynb) |
| 3 | Evaluation and calibration | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/03_evaluation_and_calibration.ipynb) |
| 4 | Explainable AI | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/04_explainable_ai.ipynb) |
| 5 | ONNX export and web demo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/notebooks/05_onnx_export_and_web_demo.ipynb) |

The [v1 white paper](https://github.com/nishthaakalia/brain-tumor-mri-classification/blob/main/v1/paper/brain_tumor_mri_white_paper.pdf) and v1 code are kept in [`v1/`](https://github.com/nishthaakalia/brain-tumor-mri-classification/tree/main/v1) for comparison.

</details>

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 📚 Research & publications

- **Nishtha Kalia** · *Brain Tumour MRI Classification: Leakage-Aware, Calibrated and Explainable EfficientNet-B0*, white paper, 2026. [v2 PDF](https://github.com/nishthaakalia/brain-tumor-mri-classification/blob/main/v2/paper/brain_tumor_mri_white_paper.pdf) · [v1 PDF](https://github.com/nishthaakalia/brain-tumor-mri-classification/blob/main/v1/paper/brain_tumor_mri_white_paper.pdf)
- Nikshep Paliwal, Rishabh Aryan, **Nishtha Kalia** · *Responsible AI on the UCI Adult dataset*: a fairness, explainability and governance audit (co-author). [Project repository](https://github.com/Rishabh-bgp/responsible-ai-uci-adult)

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 🛠️ Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3E6FD8?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-6495ED?style=for-the-badge&logo=pytorch&logoColor=white)
![timm](https://img.shields.io/badge/timm%20·%20EfficientNet-8FA8F0?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-3E6FD8?style=for-the-badge&logo=scikitlearn&logoColor=white)
![scikit-image](https://img.shields.io/badge/scikit--image-6495ED?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-8FA8F0?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-3E6FD8?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-6495ED?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-8FA8F0?style=for-the-badge&logo=python&logoColor=white)
![Captum](https://img.shields.io/badge/Captum%20·%20XAI-3E6FD8?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-6495ED?style=for-the-badge&logo=onnx&logoColor=white)
![ONNX Runtime Web](https://img.shields.io/badge/ONNX%20Runtime%20Web-8FA8F0?style=for-the-badge&logo=onnx&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-3E6FD8?style=for-the-badge&logo=javascript&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-6495ED?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-8FA8F0?style=for-the-badge&logo=googlecolab&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-3E6FD8?style=for-the-badge&logo=latex&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-6495ED?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-8FA8F0?style=for-the-badge&logo=githubpages&logoColor=white)

</div>

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 🌸 GitHub streak

<div align="center">

![GitHub streak for nishthaakalia](https://streak-stats.demolab.com/?user=nishthaakalia&hide_border=true&background=EAF5FF&ring=6495ED&fire=8FA8F0&currStreakLabel=3E6FD8&sideLabels=3E6FD8&currStreakNum=1E3A6E&sideNums=1E3A6E&dates=6495ED&stroke=BFE3FA)

</div>

<div align="center"><img src="./assets/divider.svg" alt="" width="70%"/></div>

### 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-nishtha.kalia.2411%40gmail.com-6495ED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nishtha.kalia.2411@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--7522--1221-3E6FD8?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-7522-1221)
[![GitHub](https://img.shields.io/badge/GitHub-nishthaakalia-8FA8F0?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nishthaakalia)

<sub>Thanks for visiting 💙</sub>

</div>
