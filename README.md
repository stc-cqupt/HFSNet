# HFSNet -TGRS 2024
The codes for Joint Classification of Hyperspectral and LiDAR Data Using Height Information Guided Hierarchical Fusion-and-Separation Network. 

Citation
---------------------

**Please kindly cite the papers if this code is useful and helpful for your research.**

T. Song, Z. Zeng, C. Gao, H. Chen and J. Li, "Joint Classification of Hyperspectral and LiDAR Data Using Height Information Guided Hierarchical Fusion-and-Separation Network," in IEEE Transactions on Geoscience and Remote Sensing, vol. 62, pp. 1-15, 2024, Art no. 5505315, doi: 10.1109/TGRS.2024.3353775.

@ARTICLE{HFSNet,
  author={Song, Tiecheng and Zeng, Zheng and Gao, Chenqiang and Chen, Haonan and Li, Jun},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Joint Classification of Hyperspectral and LiDAR Data Using Height Information Guided Hierarchical Fusion-and-Separation Network}, 
  year={2024},
  volume={62},
  number={},
  pages={1-15},
  keywords={Laser radar;Feature extraction;Transformers;Data mining;Convolution;Convolutional neural networks;Hyperspectral imaging;Classification;deep learning;hyperspectral image (HSI);light detection and ranging (LiDAR) data;transformer},
  doi={10.1109/TGRS.2024.3353775}}

System-specific notes
---------------------
The codes of networks were tested using PyTorch 1.10 version (CUDA 11.3) in Python 3.7 on Ubuntu system.


How to use it?
---------------------
Here an example experiment is given by using **Trento data**. Directly run **demo.py** functions with different network parameter settings to produce the results. Please note that due to the randomness of the parameter initialization, the experimental results might have slightly different from those reported in the paper.

For the datasets of Trento, you can download the data we use from the following links:
https://github.com/danfenghong/IEEE_GRSL_EndNet 


If you want to run the code in your own data, you can accordingly change the input (e.g., data, labels) and tune the parameters.

If you encounter the bugs while using this code, please do not hesitate to contact us.
 
Zheng Zeng, Email: s210101006@stu.cqupt.edu.cn
   
****
V1, V2: fixed some kernel sizes (2024-3-8) 

For new updated codes, please refer to https://github.com/Jack-zz-ze/HFSNet
