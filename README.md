# A morphological difference and statistically sparse transformer-based deep neural network for medical image segmentation
  
论文地址：https://doi.org/10.1016/j.asoc.2025.113052

Medical image segmentation plays a pivotal role in enhancing disease diagnosis and treatment planning.However, existing methods often struggle with the complexity of lesion boundaries and the computational demands of Transformer-based approaches. To address these challenges, we propose a morphological difference and statistically sparse Transformer-based deep neural network for medical image segmentation, termed MDSSFormer. It comprises two critical modules: the dual branch encoder (DBEncoder) module, and the morphological difference catcher (MDC). To extract abundant information at different aspects, a novel DBEncoder module integrates the capability of the convolutional neural network-based method in capturing local texture and the ability of the Transformer-based method in modeling global information. Compared to the conventional feature extraction methods, DBEncoder achieves comprehensive improvement. Furthermore, the statistics-based sparse Transformer (SSFormer) module develops an innovative statistical analysis and an adaptive patchdividing strategy to perform attention-computing, which addresses the computational challenges associated with conventional Transformer-based models. Finally, considering the impacts of the blurry and complex boundaries, the MDC module employs the morphological operation and differential information extractor to refine the details, which achieves high-precision boundary understanding. Experimental results on five public datasets demonstrate MD-SSFormer’s superior performance, achieving state-of-the-art Dice scores of 83.60% on ISIC 2017, 79.52 % on Kvasir-SEG, 61.89 % on BUSI, 78.62 % on BraTS21, and 85.85 % on 3DIRCADb, outperforming other methods in accuracy, precision, and computational efficiency respectively.

![image](https://github.com/NewOneNow/MD-SSFormer/assets/128780618/b7c032bb-be83-4020-b5ec-7988326c245d)  
The overview of the MD-SSFormer.

![image](https://github.com/NewOneNow/MD-SSFormer/assets/128780618/59c2c7dd-4830-44c8-a3df-52427cf44378)  
The proposed SSFormer module.

![image](https://github.com/NewOneNow/MD-SSFormer/assets/128780618/3d130e10-6e2a-4b3a-ad63-439b1d5294b6)  
The MDC module.  

# Citation:

Dongxu Cheng, Zifang Zhou, Hao Li, Jingwen Zhang, Yan Yang. A morphological difference and statistically sparse transformer-based deep neural network for medical image segmentation[J]. Applied Soft Computing, 2025, 174: 113052.
