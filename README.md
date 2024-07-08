# SCUT_PV_v1
This repository is the Large-scale SCUT Palm Vein Database Version 1 (SCUT\_PV\_v1) and benchmark for on-the-fly palm vein recognition from our paper:   
__Palm Vein Recognition under Unconstrained and Weak-cooperative Conditions.   2024 IEEE Transactions on Information Forensics and Security__  
By Dacan Luo, Yitao Qiao, Di Xie, Shifeng Zhang and Wenxiong Kang.  


## Abstract
Contactless palm vein has attracted significant attention for its high security, stability, and user-friendliness. However, current contactless palm vein recognition predominantly relies on databases collected from platforms with spatial and temporal constrained design, which inadequately reflect relaxed palm vein imaging circumstances. This paper proposes a novel manner called on-the-fly palm vein that frees the user's palm from spatial and temporal constraints, enabling palm vein recognition under unconstrained and weak-cooperative conditions. Firstly, Designing efficient and user-friendly palm vein imaging and authentication via two dynamic palm motions is proposed, resulting in an on-the-fly palm vein recognition platform. Next, a large-scale and challenging palm vein database, SCUT Palm Vein Database Version 1 (SCUT_PV_v1), is constructed. It is the first palm vein database with images collected under unconstrained and weak-cooperative conditions, encompassing a wider range of palm pose variations, grayscale variations, and lower-quality images. Finally, a lightweight and efficient Adaptive Margin Palm Vein Authentication Network (AMPVNet) is proposed as a baseline for the SCUT_PV_v1, where a vein pattern-specific convolutional neural network (CNN) is designed to extract features and a tailored online data augmentation method, combining Random Perspective Transformation (RPT) with Random Grayscale Adjustment (RGA), is proposed to enrich the diversify of out-of-plane palm pose and grayscale variations. Extensive experimental results demonstrate the effectiveness of our proposed methods. As the first work for palm vein recognition under unconstrained and weak-cooperation conditions, the AMPVNet achieves a promising accuracy and computation result while maintaining robustness to palm pose and grayscale variations. The SCUT_PV_ v1 database will be public at https://github.com/SCUT-BIP-Lab/SCUT_PV_v1.


## Database
**SCUT Palm Vein Database Version 1 (SCUT_PV_v1) **
For fair comprison to this field, please strictly follow the protocols in our paper (__Section V-A__ for). The database division files and samples are provided.

--__CSV/SCUT_PV_V1_1100_train.csv__: the .csv file of training set.  
--__CSV/SCUT_PV_V1_1100_pair_test.csv__: the .csv file of test set. 
--__Sample/RAW__: Raw samples provided to understand this database in detail. 
--__Sample/ROI__: Corresponding scaled ROI.   

## Request
The __SCUT_PV_v1__ is publicly available(free of charge) to the research community. Unfortunately, due to privacy reasons, we cannot provide the database for commercial use.

Those interested in obtaining the whole database should download [release agreement](https://github.com/SCUT-BIP-Lab/LFMB-3DFB/blob/main/SCUT%20LFMB-3DFB%20Database%20Release%20Agreement.docx), and send by e-mail one signed and scanned copy to scutbip@outlook.com.

While reporting results using the __SCUT_PV_v1__, please cite the following article:    

@article{Luo2024PalmVR,
  title={Palm Vein Recognition Under Unconstrained and Weak-Cooperative Conditions},
  author={Dacan Luo and Yitao Qiao and Di Xie and Shifeng Zhang and Wenxiong Kang},
  journal={IEEE Transactions on Information Forensics and Security},
  year={2024},
  volume={19},
  pages={4601-4614}
}


## Contact
Da can Luo   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641   
gmudacanluo@gmail.com


Prof. Kang Wenxiong   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology   
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641      
auwxkang@scut.edu.cn   
