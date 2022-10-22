# ADMNNet
ADMNNet for Underwater image enhancement  
Attention-Guided Dynamic Multi-Branch Neural Network for Underwater Image Enhancement 
If you use our code, please cite our paper and hit the star at the top-right corner. Thanks!   
@article{YAN2022110041,  
title = {Attention-guided dynamic multi-branch neural network for underwater image enhancement},   
journal = {Knowledge-Based Systems},   
pages = {110041},   
year = {2022},   
issn = {0950-7051},   
doi = {https://doi.org/10.1016/j.knosys.2022.110041},   
url = {https://www.sciencedirect.com/science/article/pii/S0950705122011340},   
author = {Xiaohong Yan and Wenqiang Qin and Yafei Wang and Guangyuan Wang and Xianping Fu},   
keywords = {Underwater imaging, Image enhancement, Multiple branch network, Receptive field, Attention mechanism},   
abstract = {Underwater images often suffer from quality deteriorations such as color deviation, reduced contrast, and blurred details due to wavelength-dependent light absorption and scattering in water media. Recently, convolutional neural networks (CNNs) have achieved impressive success in underwater image enhancement (UIE). However, there is still room for improvement in terms of representational capability and receptive field (RF)/channel variant ability in almost all CNN-based UIE networks. To treat these problems, we propose an attention-guided dynamic multibranch neural network (ADMNNet) to obtain high-quality underwater images. Different from existing CNN-based UIE networks that generally share a fixed RF size of artificial neurons in one feature layer, we propose an attention-guided dynamic multibranch block (ADMB) to boost the diversity of feature representations by merging the properties of different RFs into a single-stream structure. Concretely, ADMB includes two main components, namely, a dynamic feature selection module (DFSM) and a multiscale channel attention module (MCAM). Inspired by the selective kernel mechanism in the visual cortex, we incorporate a nonlinear strategy into the DFSM that allows the neurons to adjust their RF sizes reasonably by using soft attention to achieve dynamic fusion of multiscale features. In the MCAM, channel attention is designed to exploit the interdependencies among the channelwise features extracted from different branches. Our ADMNNet can obtain better visual quality of underwater images captured under diverse scenarios and achieves superior qualitative and quantitative performance compared to state-of-the-art UIE methods.}   
}    
