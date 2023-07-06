<h1 align="center">
  <br>
BrainSight:Leveraging-Vision Transformers for Tumor Detection
  <br>
</h1>

<p align="center">This project aims to classify brain tumors using a single slice of a T1-weighted contrast MRI scan. We explore the use of the Vision Transformer (ViT) architecture and compare the results against the ResNet-50 architecture and got to accuracy of 99.61% with efficientformer.</p>

<h2 align = "center">
<a target="_blank" href="https://colab.research.google.com/github/litvingil/BrainSight-Leveraging-Vision-Transformers-for-Tumor-Detection/blob/main/BrainSight.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
</h2>

![accuracy](images/output.png)

## Project Introduction
This project is an exploration into the potential of using neural networks for the automation of brain tumor detection and classification, which traditionally relies on the expertise of trained neuroradiologists. We investigate if a neural network, specifically the Vision Transformer (ViT) model, can effectively classify brain tumors using a single slice of a T1-weighted contrast MRI scan. 

## Methodology
Our methodology involves using a dataset comprising 3,064 images of three distinct types of brain tumors (Meningioma, Pituitary tumor, and Glioma).

![Dataset](images/tumors.png)

We employ a pre-trained ViT model obtained from Hugging Face and fine-tune it to meet our requirements. We also incorporate data augmentations to improve the robustness and generalization capabilities of our model.

### Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Image Processing

### Results
We conduct a comparative analysis between the ViT model and a baseline ResNet-50 model. Our ViT model outperformed the baseline ResNet-50 model in terms of accuracy, achieving 97.23% accuracy without augmentations and 96.90% with augmentations.

### Load pretrained model
For loading pretrained model use 
```python
from transformers import ViTForImageClassification
model = ViTForImageClassification.from_pretrained('path_to_model_dir')
```

### How to Install and Run this Project
More detailed instructions will be provided soon.

## Future Work
Our project has demonstrated the potential for integration into a clinical system, enhancing the diagnostic capabilities of physicians and saving vital time. We aim to further enhance our model by exploring additional variations of ViT and other techniques to boost its accuracy and generalization capabilities.

## Authors

- Omer Paz
- Gil Litvin
- Ari Shemesh
