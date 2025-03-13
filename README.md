# LWMS-Net: A novel defect detection network based on multi-wavelet multi-scale for steel surface defects

## Abstract

Steel surface defect detection is crucial to improve industrial product quality and reduce costs. However, attaining high detection accuracy and efficiency based on convolutional neural network (CNN) is challenging due to diversity, random position, irregular shape, low contras, and complex background interference of the defects. The originality of this work is to design a novel defect detection network based on Legendre multi-wavelet multi-scale theory (LWMS-Net) to find a subtle balance between high detection accuracy and fast detection speed. In LWMS-Net, a feature difference enhancement (FDE) module is devised to emphasize defect edges and details, improving defect feature representation and reducing irrelevant information. More importantly, a new Backbone framework of LWMS-Net is designed to effectively capture the multi-scale contextual and detailed information of the complex defects in the multi-wavelet domain, resulting in a better interpretable LWMS module and network depth reduction largely. Then, LWMS-Net is designed by incorporating the LWMS module with improved Faster region-based CNN to encompass the defect feature interactions between multi-wavelet multi-scale receptive field explicitly. Finally, the effectiveness and generalization of the proposed network are verified on NEU-DET, GC10-DET, and PV-Multi-Defect datasets, achieving high mean Average Precision (mAP) scores of 81.6%, 73.7%, and 91.2%, respectively, and outperforming state-of-the-art methods. 

### If you are interested, you can refer to the following works for more information on the LWT algorithm:
X. Zheng, Y. Huang, W. Liu, C. Cai, "LW-XNet for segmentation and classification of skin lesions from dermoscopy images", Expert Systems with Applications, 255 (2024), pp.124826, https://doi.org/10.1016/j.eswa.2024.124826.

### In the future, we plan to release the code of LWMS-Net to advance defect detection research and facilitate practical applications.

