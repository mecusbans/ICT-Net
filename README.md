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
| 2022  | EAR-U-Net |Automatic liver segmentation using efficientNet and attention-based residual U-Net in CT [(Paper)](https://link.springer.com/article/10.1007/s10278-022-00668-x) | [Code](https://github.com/ZhangXY-123/EAR-Unet)|
| 2023  | GCHA-Net   |GCHA-Net: Global context and hybrid attention network for automatic liver segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0010482522010605) | [Code](https://github.com/HuaxiangLiu/GCAU-Net)|
| 2024  | DualA-Net  |DualA-Net: A generalizable and adaptive network with dual-branch encoder for medical image segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0169260723005436) | [Code](https://github.com/Ziii1/DualA-Net)|
| 2024  | DeY-Net    |From denoising training to test-time adaptation: Enhancing domain generalization for medical image segmentation [(Paper)](https://openaccess.thecvf.com/content/WACV2024/html/Wen_From_Denoising_Training_To_Test-Time_Adaptation_Enhancing_Domain_Generalization_for_WACV_2024_paper.html) | [Code](https://github.com/WenRuxue/DeTTA)|
| 2024  | FedDUS    |FedDUS: Lung tumor segmentation on CT images through federated semi-supervised with dynamic update strategy [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0169260724001378) | [Code](https://github.com/GDPHMediaLab/FedDUS)|
| 2024  | MpMsCFMA-Net |MpMsCFMA-Net: Multi-path multi-scale context feature mixup and aggregation network for medical image segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S0952197624004500) | [Code](https://github.com/tricksterANDthug/MpMsCFMA-Net)|
| 2024  | CSSNet     |CSSNet: Cascaded spatial shift network for multi-organ segmentation [(Paper)](https://www.sciencedirect.com/science/article/pii/S0010482524000398) | [Code](https://github.com/zkyseu/CSSNet)|
| 2021  | Swin UNETR |Swin UNETR: Swin transformers for semantic segmentation of brain tumors in mri images [(Paper)](https://link.springer.com/chapter/10.1007/978-3-031-08999-2_22) | [Code](https://monai.io/research/swin-unetr)|
| 2023  | MedNeXt   |MedNeXt: Transformer-driven scaling of convnets for medical image segmentation [(Paper)](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_39) | [Code](https://github.com/MIC-DKFZ/MedNeXt)|
| 2023  | DAE-Former |DAE-Former: Dual attention-guided efficient transformer for medical image segmentation [(Paper)](https://link.springer.com/chapter/10.1007/978-3-031-46005-0_8) | [Code](https://github.com/xmindflow/DAEFormer)|
| 2023  | Hong et al.|Dual encoder network with transformer-CNN for multi-organ segmentation [(Paper)](https://link.springer.com/article/10.1007/s11517-022-02723-9) | [Code](https://github.com/zhifanghong/CNN-TransformerDualEncodeNetwork)|
| 2023  | HiFormer   |HiFormer: Hierarchical multi-scale representations using transformers for medical image segmentation [(Paper)](https://openaccess.thecvf.com/content/WACV2023/html/Heidari_HiFormer_Hierarchical_Multi-Scale_Representations_Using_Transformers_for_Medical_Image_Segmentation_WACV_2023_paper.html) | [Code](https://github.com/amirhossein-kz/HiFormer)|
| 2024  | PFD-Net    |PFD-Net: Pyramid fourier deformable network for medical image segmentation [(Paper)](https://www.sciencedirect.com/science/article/abs/pii/S001048252400386X) | [Code](https://github.com/ChaorongYang/PFD-Net)|
| 2024  | SCUNet++   |SCUNet++: Swin-unet and cnn bottleneck hybrid architecture with multi-fusion dense skip connection for pulmonary embolism ct image segmentation [(Paper)](https://openaccess.thecvf.com/content/WACV2024/html/Chen_SCUNet_Swin-UNet_and_CNN_Bottleneck_Hybrid_Architecture_With_Multi-Fusion_Dense_WACV_2024_paper.html) | [Code](https://github.com/JustlfC03/SCUNet-plusplus)|




# Medical Image Segmentation CT Datasets

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


