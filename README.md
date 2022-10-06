[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.png)](https://www.python.org/)
[![MIT Licence](https://img.shields.io/badge/License-MIT-blue.png)](https://opensource.org/licenses/mit-license.php)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.png)](https://github.com/dennishnf/unsupervised-anomaly-detection/issues)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-1abc9c.png)](https://github.com/dennishnf/unsupervised-anomaly-detection/)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Download%20and%20use%20the%20Project:%20Unsupervised%20anomaly%20detection&url=https://github.com/dennishnf/unsupervised-anomaly-detection&hashtags=anomaly,images,anomalib,unsupervised)    

Unsupervised anomaly detection using Anomalib
=============================================

## Description

This repository describes the implementation of an unsupervised anomaly detector on metallic nuts using the Anomalib library. Thereby we evaluate several state-of-the-art deep learning models such as PaDiM, PatchCore, STFPM, FastFlow and Reverse Distillation. 

The data used was The MVTEC Anomaly Detection Dataset ([MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad)), but only the metal nut dataset was used. The training was performed locally on a laptop with an NVIDIA GeForce GTX 1050 Ti GPU and Ubuntu 20.04 LTS operating system.

It is recommended to download the dataset from this [link](https://www.mydrive.ch/shares/38536/3830184030e49fe74747669442f0f282/download/420937637-1629952063/metal_nut.tar.xz), and organize the dataset in the format shown in the main notebook.

The implementation is fully described in the main notebook: **unsupervised-anomaly-detection.ipynb**.

<p align="center">
<img src=".images-readme/image-inference.png" alt="figure" width="760"/>
</p>

## Author

Dennis Hernando NÚÑEZ FERNÁNDEZ    
[https://dennishnf.com](https://dennishnf.com)


## References

- Akcay, S., Ameln, D., Vaidya, A., Lakshmanan, B., Ahuja, N., & Genc, U. (2022). Anomalib: A Deep Learning Library for Anomaly Detection. doi:10.48550/ARXIV.2202.08341    
- https://blog.ml6.eu/a-practical-guide-to-anomaly-detection-using-anomalib-b2af78147934    
- https://openvinotoolkit.github.io/anomalib/    
- https://pypi.org/project/anomalib/    
- https://www.kaggle.com/code/ipythonx/mvtec-ad-anomaly-detection-with-anomalib-library/notebook    
- https://www.mvtec.com/company/research/datasets/mvtec-ad    


