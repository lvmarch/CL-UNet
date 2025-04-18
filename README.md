# Lightweight Temporal Consistent Weakly Supervised Learning for Echocardiographic Video Segmentation

## Authors
Jinrong Lv, Ning Chen, Weili Jiang, Xun Gong*  
**Corresponding author:** Xun Gong  
*IEEE Member*  

**Affiliations:**  
School of Computing and Artificial Intelligence, Southwest Jiaotong University, Chengdu, Sichuan, China  

## Abstract
Echocardiographic video is essential for computer-aided diagnosis (CAD) of cardiovascular disease. Their dynamic object left ventricle (LV) segmentation results can be used to accurately quantify ventricular volumes, providing an important basis for assessing cardiac structure. Thanks to advances in deep learning, existing methods have achieved high segmentation accuracy, but these generally have high parametric and computational costs, making it difficult to be deployed and applied in low-cost ultrasound equipment in primary hospitals. In addition, frame-by-frame annotation of echocardiographic videos is a labor-intensive task, and it is difficult for clinicians to have time to annotate echocardiographic videos frame-by-frame, resulting in existing datasets that typically include sparse annotations of only two frames: end-diastolic (ED) frames and end-systolic (ES) frames. In this work, we propose a lightweight 3D U-Net architecture with parallel banded convolutional branches. Compared to the standard 3D U-Net, it reduces the number of parameters by about seven times without degrading the segmentation accuracy. To achieve accurate frame-by-frame segmentation of the left ventricle in sparsely annotated echocardiography videos, we impose temporal consistency constraints on the training process by extracting cardiac cycle signals from the videos. This enhances the segmentation network's understanding of LV motion and improves its segmentation accuracy and temporal consistency on unlabeled frames. We validate the effectiveness of the proposed method on three echocardiography video public datasets, EchoNet Dynamic, CAMUS, and EchoNet Pediatric. Extensive experimental results show that our method has better performance than all previous state-of-the-art methods with few parameters and computational overheads.

## Status
This paper is currently under peer review. The code will be released upon acceptance.

## Contact
- **Jinrong Lv**: lvjinrong@my.swjtu.edu.cn, lvjinrong.23@gmail.com  
- **Ning Chen**: chenning@my.swjtu.edu.cn  
- **Weili Jiang**: jiangweili@swjtu.edu.cn, weilijiang111@gmail.com  
- **Xun Gong**: xgong@swjtu.edu.cn

## Todo
- [ ] Code release after paper acceptance
