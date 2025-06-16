# Lightweight Temporal Consistent Weakly Supervised Learning for Echocardiographic Video Segmentation

## Authors
Jinrong Lv, Ning Chen, Weili Jiang, Xun Gong 

**Corresponding author:** Xun Gong 

**Affiliations:**  
School of Computing and Artificial Intelligence, Southwest Jiaotong University, Chengdu, Sichuan, China  

## Abstract
Echocardiography videos are crucial for Computer-Aided Diagnosis (CAD) of cardiovascular diseases. For example, Left Ventricular (LV) segmentation results can be used to accurately quantify ventricular volume, providing essential insights for assessing cardiac function. However, frame-by-frame annotation of Echocardiography videos is a labor-intensive task, and clinicians often lack the time to annotate each frame. As a result, existing datasets typically contain sparse annotations limited to only two frames: End-Diastole (ED) and End-Systole (ES), which restricts the model's ability to develop a comprehensive understanding of cardiac motion during training. Additionally, Existing video segmentation methods typically involve high parameter counts and computational costs, making their deployment and application on low-cost ultrasound equipment in primary healthcare settings challenging. In this work, we propose a lightweight 3D U-Net architecture with parallel banded convolutional branches. Compared to the standard 3D U-Net, it reduces the number of parameters by about seven times without degrading the segmentation accuracy. To achieve accurate frame-by-frame segmentation of the left ventricle in sparsely annotated echocardiography videos, we impose temporal consistency constraints on the training process by extracting cardiac cycle signals from the videos. This enhances the segmentation network's understanding of LV motion and improves its segmentation accuracy and temporal consistency on unlabeled frames. We validate the effectiveness of the proposed method on three echocardiography video public datasets, EchoNet Dynamic, CAMUS, and EchoNet Pediatric. Extensive experimental results show that our method has better performance than all previous state-of-the-art methods with few parameters and computational overheads.

## Status
This paper is currently under peer review. The code will be released upon acceptance.

## Contact
- **Jinrong Lv**: lvjinrong@my.swjtu.edu.cn, lvjinrong.23@gmail.com  
- **Ning Chen**: chenning@my.swjtu.edu.cn  
- **Weili Jiang**: jiangweili@swjtu.edu.cn, weilijiang111@gmail.com  
- **Xun Gong**: xgong@swjtu.edu.cn

## Todo
- [ ] Code release after paper acceptance
