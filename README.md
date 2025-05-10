# Mapping the Layers of the Ocean Floor With a Convolutional Neural Network

<p align="center">
  <img src="Assets/CBPF.jpg" width="200"/>
</p>

This project, developed at the [Brazilian Center for Physics Research (CBPF)](http://portal.cbpf.br/), focuses on mapping the layers of the ocean floor using a Convolutional Neural Network (CNN). The primary goal is to analyze geological structures and understand seabed composition, which has a significant impact on the oil industry.

## 🌟 Key Achievement

This research resulted in the publication of a paper on arXiv:
**[Mapping the Layers of the Ocean Floor With a Convolutional Neural Network](https://arxiv.org/abs/2412.05329)** 

<p align="center">
  <a href="https://arxiv.org/abs/2412.05329" target="_blank">
    <img src="Assets/ArXiv_logo.png" alt="arXiv logo" width="100"/>
  </a>
</p>

## 📖 Project Overview

The project utilizes machine learning techniques, specifically Convolutional Neural Networks, to segment and analyze images of the ocean floor. This allows for the identification and mapping of different geological layers. The methodology involves several stages, including image preprocessing, model training for segmentation, and post-processing of the results.

The work is divided into several experimental stages, as detailed in the Jupyter Notebooks within the `EXPA/ML-Segmentation/` directory:

- **Etapa1-Segmentation.ipynb:** Initial image segmentation using a CNN.
- **Etapa2-Kmeans.ipynb:** Application of K-means clustering for further refinement.
- **Etapa3-Watersherd&Tabela.ipynb:** Utilization of watershed algorithms and generation of data tables with morphological parameters.

## 💻 Tech Stack

This project leverages a variety of Python libraries and tools:

- **Core Language:** Python ![Python][python-shield]
- **Development Environment:** Jupyter Notebooks ![Jupyter Notebooks][jupyter-shield]
- **Machine Learning & Deep Learning:**
  - PyTorch ![PyTorch][pytorch-shield]
  - Scikit-image ![Scikit-image][scikit-image-shield]
- **Image Processing:**
  - OpenCV (cv2) ![OpenCV][opencv-shield]
- **Numerical Computation & Data Analysis:**
  - NumPy ![NumPy][numpy-shield]
  - Pandas ![Pandas][pandas-shield]
  - SciPy ![SciPy][scipy-shield]
- **Plotting & Visualization:**
  - Matplotlib ![Matplotlib][matplotlib-shield]
- **Other:**
  - Google Colab (for cloud-based notebook execution) ![Google Colab][google-colab-shield]

[python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[pytorch-shield]: https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[scikit-image-shield]: https://img.shields.io/badge/scikit--image-0096CF?style=for-the-badge&logo=scikit-image&logoColor=white
[opencv-shield]: https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white
[numpy-shield]: https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white
[pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[scipy-shield]: https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white
[matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white
[google-colab-shield]: https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black
[arxiv-shield]: https://arxiv.org/abs/2412.05329

## 🚀 Getting Started

To explore the project:

1. Clone the repository.
2. Ensure you have Python and the necessary libraries installed (refer to the import statements in the Jupyter Notebooks for a complete list).
3. Open and run the Jupyter Notebooks in the `EXPA/ML-Segmentation/` directory to see the different stages of the analysis.

## 📄 License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
