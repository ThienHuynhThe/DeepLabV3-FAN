# DeepLabV3-FAN
Abstract - As a cutting-edge deep encoder-decoder architecture, DeepLabV3+ has been realized as a state-of-the-art solution for image segmentation. Furthermore, DeepLabV3+ has great potential for semantic segmentation of aerial images captured by unmanned aerial vehicles (UAVs) for aerial and remote sensing applications. This is thanks to an Atrous Spatial Pyramid Pooling (ASPP) block deployed in its encoder with multiple atrous convolutional layers to enrich diversified feature extraction and learning efficiency. However, the DeepLabV3 + encoder-decoder architecture has some limitations, including the lack of information during the upsampling process and some inappropriate customizations that cause incorrect segmentation. To address these shortcomings, we introduce an efficient architecture with a novel Feature Aggregation Network (FAN), which facilitates the extraction of features across multiple scales and stages. Concurrently, we apply some adaptive upgrades to the ASPP block, involving a new set of dilation factors that are adept at accommodating low-resolution inputs.
As a result, our improved remote sensing segmentation model achieves significant performance gains when evaluated on a real-world data set: Global precision improves by at least $5.39\%$, mean intersection-over-union (IoU) increases by $10.97\%$, and mean boundary-F1 score (BFScore) improves by $11.3\%$.
These advances lead to a more precise identification of urban classes, resulting in a greater precision in the segmentation task.

<img src="https://github.com/ThienHuynhThe/DeepLabV3-FAN/blob/main/deeplabv3%2BFAN.png" height="815px" width="770px" >

We provide the source code of this work in Matlab, including:<br>

  - training_test_program.m: this file is used to train and test performance of deep semantic segmentation model<br>
  - lgraph_deeplabv3+_resnet50.mat: this contains the architecture of deep network with trained backbone Resnet50. This is used for training stage in training_test_program.m in the case of training = 1.<br>
  - trained_deeplabv3+_resnet50.mat: this contains the deep model that is already trained on Vaihingen using backbone Resnet50. This is just used for evaluation stage.

The work of this code is currently revised for considering publication on IGRSL.
If there is any error or need to be discussed, please email to [Thien Huynh-The](https://sites.google.com/site/thienhuynhthe/home) via thienht@kumoh.ac.kr.
