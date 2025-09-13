# DL-Arsenicosis-Diagnosis
A deep learning project for diagnosing arsenicosis from mobile-captured skin images. The system employs CNNs and ViTs, integrates LIME for explainability, and includes web deployment for accessible real-world use.

## Libraries Used

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.14-orange)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.14-red)](https://keras.io/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.1-darkred)](https://pytorch.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-green)](https://seaborn.pydata.org/)
[![LIME](https://img.shields.io/badge/LIME-0.2-yellow)](https://github.com/marcotcr/lime)


## Features
- Data Curation from various sources. Images captured by mobile phones for arsenic-affected skin regions, along with 19 other skin lesions.
- Training CNN and Transformer architectures
- Explains predictions using LIME and Grad-CAM
- External Validation
- Web deployment using Streamlit (or Flask/Gradio) - (in progress)
  

## DL Models Deployed

[![VGG16](https://img.shields.io/badge/VGG16-ImageNet-orange)](https://keras.io/api/applications/vgg/#vgg16-function)
[![InceptionV3](https://img.shields.io/badge/InceptionV3-ImageNet-blue)](https://keras.io/api/applications/inceptionv3/)
[![EfficientNetB0](https://img.shields.io/badge/EfficientNetB0-ImageNet-green)](https://keras.io/api/applications/efficientnet/)
[![Xception](https://img.shields.io/badge/Xception-ImageNet-purple)](https://keras.io/api/applications/xception/)
[![MobileNetV2](https://img.shields.io/badge/MobileNetV2-ImageNet-red)](https://keras.io/api/applications/mobilenet/#mobilenetv2-function)
[![ViT](https://img.shields.io/badge/ViT-PyTorch-lightblue)](https://github.com/facebookresearch/deit)
[![Swin Transformer](https://img.shields.io/badge/Swin-Transformer-lightgreen)](https://github.com/microsoft/Swin-Transformer)
[![DeiT](https://img.shields.io/badge/DeiT-PyTorch-yellow)](https://github.com/facebookresearch/deit)

## Results

![App Screenshot](https://github.com/newaz-aa/DL-Arsenicosis-Diagnosis/blob/main/Results/Xception_training_curves.png)

![App Screenshot](https://github.com/newaz-aa/DL-Arsenicosis-Diagnosis/blob/main/Results/Xception_confusion_matrix.png)

![App Screenshot](https://github.com/newaz-aa/DL-Arsenicosis-Diagnosis/blob/main/Data/Arsenic_2x2_block_2.png)

## Model Deployment

Details can be found in the following repositories -
- https://github.com/RSS-code/Arsenic-classifier_videos
- https://github.com/mmehzad/newazsir_ra

## 📑 Citation

If you find this work useful, please cite our paper:

```bibtex
@article{newaz2025arsenicosis,
  title   = {An End-to-End Deep Learning Framework for Arsenicosis Diagnosis Using Mobile-Captured Skin Images},
  author  = {Newaz, Asif and [co-authors]},
  journal = {arXiv preprint arXiv:2509.08780},
  year    = {2025}
}

