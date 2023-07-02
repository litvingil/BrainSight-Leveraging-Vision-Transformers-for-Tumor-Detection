# BrainSight-Leveraging-Vision-Transformers-for-Tumor-Detection
This project aims to classify brain tumors using a single slice of a T1-weighted contrast MRI scan. We explore the use of the Vision Transformer (ViT) architecture and compare the results against the ResNet-50 architecture.

## Project Introduction
This project is an exploration into the potential of using neural networks for the automation of brain tumor detection and classification, which traditionally relies on the expertise of trained neuroradiologists. We investigate if a neural network, specifically the Vision Transformer (ViT) model, can effectively classify brain tumors using a single slice of a T1-weighted contrast MRI scan. 

## Methodology
Our methodology involves using a dataset comprising 3,064 images of three distinct types of brain tumors (Meningioma, Pituitary tumor, and Glioma). We employ a pre-trained ViT model obtained from Hugging Face and fine-tune it to meet our requirements. We also incorporate data augmentations to improve the robustness and generalization capabilities of our model.

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Image Processing

## Results
We conduct a comparative analysis between the ViT model and a baseline ResNet-50 model. Our ViT model outperformed the baseline ResNet-50 model in terms of accuracy, achieving 97.23% accuracy without augmentations and 96.90% with augmentations.

## How to Install and Run this Project
More detailed instructions will be provided soon.

## Future Work
Our project has demonstrated the potential for integration into a clinical system, enhancing the diagnostic capabilities of physicians and saving vital time. We aim to further enhance our model by exploring additional variations of ViT and other techniques to boost its accuracy and generalization capabilities.

## Contributions
This project is the result of joint work between a team of data scientists and a neurologist. Contributions are welcome. Please see the contributions guide (to be added soon) for details on how to contribute.
