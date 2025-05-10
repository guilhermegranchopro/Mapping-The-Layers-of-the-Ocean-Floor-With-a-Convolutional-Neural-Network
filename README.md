# Mapping the Layers of the Ocean Floor With a Convolutional Neural Network

<img src="Assets/CBPF.jpg" width="300"/>

This project, developed at the [Brazilian Center for Physics Research (CBPF)](http://portal.cbpf.br/), focuses on mapping the layers of the ocean floor using a Convolutional Neural Network (CNN). The primary goal is to analyze geological structures and understand seabed composition, which has a significant impact on the oil industry.

## 🌟 Key Achievement

This research resulted in the publication of a paper on arXiv:
**[Mapping the Layers of the Ocean Floor With a Convolutional Neural Network](https://arxiv.org/abs/2412.05329)**

## 📖 Project Overview

The project utilizes machine learning techniques, specifically Convolutional Neural Networks, to segment and analyze images of the ocean floor. This allows for the identification and mapping of different geological layers. The methodology involves several stages, including image preprocessing, model training for segmentation, and post-processing of the results.

The work is divided into several experimental stages, as detailed in the Jupyter Notebooks within the `EXPA/ML-Segmentation/` directory:

- **Etapa1-Segmentation.ipynb:** Initial image segmentation using a CNN.
- **Etapa2-Kmeans.ipynb:** Application of K-means clustering for further refinement.
- **Etapa3-Watersherd&Tabela.ipynb:** Utilization of watershed algorithms and generation of data tables with morphological parameters.

## 💻 Tech Stack

This project leverages a variety of Python libraries and tools:

- **Core Language:** Python
- **Development Environment:** Jupyter Notebooks
- **Machine Learning & Deep Learning:**
  - PyTorch
  - Scikit-image
- **Image Processing:**
  - OpenCV (cv2)
- **Numerical Computation & Data Analysis:**
  - NumPy
  - Pandas
  - SciPy
- **Plotting & Visualization:**
  - Matplotlib
- **Other:**
  - Google Colab (for cloud-based notebook execution)

## 🚀 Getting Started

To explore the project:

1. Clone the repository.
2. Ensure you have Python and the necessary libraries installed (refer to the import statements in the Jupyter Notebooks for a complete list).
3. Open and run the Jupyter Notebooks in the `EXPA/ML-Segmentation/` directory to see the different stages of the analysis.

## 📄 License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
