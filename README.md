# ICT-Net: An Integrated Convolution and Transformer-Based Network for Complex Liver and Liver Tumor Region Segmentation

Background: Automatic segmentation of liver regions as well as liver lesions such as hepatocellular carcinoma (HCC) from computed tomography (CT) images is critical for accurate diagnosis and therapy planning. With the advent of deep learning techniques such as transformers, computer-aided diagnostic tools (CADs) have the potential to increase the accuracy of liver tumor diagnosis, progression, and treatment planning. However, two major challenges remain: (1) existing models struggle to extract robust spatial features for accurate liver and liver lesion segmentation, and (2) publicly available liver datasets with HCC annotations are limited. Methods: We first present a new liver dataset acquired from Chongqing University Cancer Hospital (CCH-LHCC-CT) with HCC annotations. Second, we developed a novel deep learning architecture (ICT-Net), which is constructed based on a pretrained transformer encoder in conjunction with an advanced feature upscaling and enhanced convolution-transformer decoder formation. Results: We performed liver and liver tumor segmentation on the CCH-LHCC-CT and three public CT liver datasets. The proposed ICT-Net architecture achieves superior accuracy (higher ACC/DSC/IoU, lower HD95) across all datasets. Conclusions: We construct a novel deep-learning architecture that produces robust information for liver and liver tumor segmentation. The statistical and visual results demonstrate that the proposed ICT-Net outperforms other existing approaches investigated in this study in terms of ACC, DSC, and IoU. Clinical Translation Statement: ICT-Net enhances surgical planning accuracy through precise tumor margin delineation and improves therapy response assessment reliability, which holds meaningful promise to support more precise and effective clinical therapeutic strategies for patients with HCC. [(Paper link)](https://doi.org/10.1109/JTEHM.2025.3586470)

#  ICT-Net Architecture

![Figure2](https://github.com/mecusbans/ICT-Net/blob/051e6a89fd764d2bca08c60bb2f4f690175df47e/Folders/Figure2.png)

# The schematic illustration of CT slices from the CCH-LHCC-CT dataset highlights various challenges in liver and liver tumor segmentation
![Figure1](https://github.com/mecusbans/ICT-Net/blob/051e6a89fd764d2bca08c60bb2f4f690175df47e/Folders/Figure1.png)

# Segmentation Results on the CCH-LHCC-CT Tumor Dataset
![Figure7](https://github.com/mecusbans/ICT-Net/blob/051e6a89fd764d2bca08c60bb2f4f690175df47e/Folders/Figure7.pdf)


# Requirements
Python>= 3.7, Pytorch >= 2.0.0

# Experimental Setting
All experiments were conducted using an NVIDIA GeForce RTX 2080 Ti GPU

# CNN and Transformer-based Models for Medical Image Segmentation

| Date    | Model     |Title                                                                                                                                                      | Code |
| :---:   | :---:     | :---:                                                                                                                                                     | :---:|
| 2022  | MCI-Net   |MCI-Net: Multi-scale context integrated network for liver CT image segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0045790622003408) | [Code](https://github.com/Xie-Xiwang/MCI-Net)|



# Medical Image Segmentation Ultrasound and CT Datasets

| Year    | Dataset     | Tissue  Type                           | Link|
| :---:   | :---:     | :---:                                                          | :---:|
| 2023  | LiTs| Liver| [Link](https://www.sciencedirect.com/science/article/pii/S1361841522003085) |
| 2010  | 3D-IRCADb-1  | Liver | [Link](https://www.kaggle.com/datasets/sarahelqersh/3dircadb1) |
| 2021  | CHAOS | Liver | [Link](https://chaos.grand-challenge.org/) |



#   Contact
mecusbans@gmail.com

#   Acknowledgments
The authors thank the Chongqing University Cancer hospital for their support.


# Cite this article
Atabansi CC, Li H, Wang S, Nie J, Liu H, Xu B, Zhou X, Li D. ICT-Net: An Integrated Convolution and Transformer-Based Network for Complex Liver and Liver Tumor Region Segmentation. IEEE Journal of Translational Engineering in Health and Medicine. 2025 May 5:128022.


