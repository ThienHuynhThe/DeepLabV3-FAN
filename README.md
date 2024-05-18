# DeepLabV3-FAN
Abstract - As a cutting-edge deep encoder-decoder architecture, DeepLabV3+ has been realized as a state-of-the-art solution for image segmentation. Furthermore, DeepLabV3+ has great potential for semantic segmentation of aerial images captured by unmanned aerial vehicles (UAVs) for aerial and remote sensing applications. This is thanks to an Atrous Spatial Pyramid Pooling (ASPP) block deployed in its encoder with multiple atrous convolutional layers to enrich diversified feature extraction and learning efficiency. However, the DeepLabV3 + encoder-decoder architecture has some limitations, including the lack of information during the upsampling process and some inappropriate customizations that cause incorrect segmentation. To address these shortcomings, we introduce an efficient architecture with a novel Feature Aggregation Network (FAN), which facilitates the extraction of features across multiple scales and stages. Concurrently, we apply some adaptive upgrades to the ASPP block, involving a new set of dilation factors that are adept at accommodating low-resolution inputs.
As a result, our improved remote sensing segmentation model achieves significant performance gains when evaluated on a real-world data set: Global precision improves by at least $5.39\%$, mean intersection-over-union (IoU) increases by $10.97\%$, and mean boundary-F1 score (BFScore) improves by $11.3\%$.
These advances lead to a more precise identification of urban classes, resulting in a greater precision in the segmentation task.

<img src="https://github.com/ThienHuynhThe/MCNet/blob/master/overall_mcnet_architecture.png" height="204px" width="548px" >
<img src="https://github.com/ThienHuynhThe/MCNet/blob/master/mblock_mcnet.png" height="371px" width="548px" >

How to cite 

T. Huynh-The, C. Hua, Q. Pham and D. Kim, "MCNet: An Efficient CNN Architecture for Robust Automatic Modulation Classification," in IEEE Communications Letters, vol. 24, no. 4, pp. 811-815, April 2020, doi: 10.1109/LCOMM.2020.2968030.

@ARTICLE{mcnet2020CommLett,
  author={T. {Huynh-The} and C. {Hua} and Q. {Pham} and D. {Kim}},
  journal={IEEE Communications Letters}, 
  title={MCNet: An Efficient CNN Architecture for Robust Automatic Modulation Classification}, 
  year={2020},
  volume={24},
  number={4},
  pages={811-815},}

We provide the MATLAB code of automatic modulation classification of this paper.
If there is any error or need to be discussed, please email to [Thien Huynh-The](https://sites.google.com/site/thienhuynhthe/home) via thienht@kumoh.ac.kr.
