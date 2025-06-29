# Lightweight Temporal Consistent Weakly Supervised Learning for Echocardiography Video Segmentation

## Authors
Jinrong Lv, Ning Chen, Weili Jiang, Xun Gong 

**Corresponding author:** Xun Gong 

**Affiliations:**  
School of Computing and Artificial Intelligence, Southwest Jiaotong University, Chengdu, Sichuan, China  

## Abstract
Echocardiography videos play a vital role in computer-aided diagnosis (CAD) of cardiovascular diseases. For instance, accurate segmentation of the left ventricle (LV) enables precise quantification of ventricular volumes and offers critical insights into cardiac function. However, frame-by-frame annotation of echocardiography videos is labor-intensive, and clinicians often lack the time to label every frame. As a result, existing datasets typically contain sparse annotations limited to two frames: end-diastole (ED) and end-systole (ES). This sparsity hinders models from fully learning the dynamics of cardiac motion. In addition, current video segmentation methods often involve large parameter counts and high computational costs, making them unsuitable for deployment on low-cost ultrasound devices in primary healthcare settings. In this work, we propose a lightweight 3D U-Net architecture called CL-UNet that reduces the number of parameters by approximately 7$\times$ compared to the standard 3D U-Net, without compromising segmentation accuracy. More importantly, to achieve accurate frame-wise LV segmentation from sparsely annotated echocardiography videos, we propose a temporal consistency loss (TCL), which enforces learning of cardiac motion patterns by leveraging estimated cardiac cycle signals. To the best of our knowledge, this is the first work to introduce temporal consistency constraints for echocardiography video segmentation. This enhances the segmentation network’s understanding of LV motion. We validate our approach on three public echocardiography video datasets: EchoNet-Dynamic, CAMUS, and EchoNet-Pediatric. Extensive experiments demonstrate that our method outperforms all prior state-of-the-art approaches, while requiring significantly fewer parameters and computational resources.

## Status
This paper is currently under peer review. The code will be released upon acceptance.

## Contact
- **Jinrong Lv**: lvjinrong@my.swjtu.edu.cn, lvjinrong.23@gmail.com  
- **Ning Chen**: chenning@my.swjtu.edu.cn  
- **Weili Jiang**: jiangweili@swjtu.edu.cn, weilijiang111@gmail.com  
- **Xun Gong**: xgong@swjtu.edu.cn

## Todo
- [ ] Code release after paper acceptance.
