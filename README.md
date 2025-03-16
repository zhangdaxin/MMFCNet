# MMFCNet：A Multi-Method Fusion Cascade Network for 3D Object Detection in Point Cloud

## Abstract
<div style="text-align: justify">The primary objective of this research is to develop efficient algorithms for detecting objects in 3D LiDAR point clouds, especially in challenging outdoor environments, using deep learning techniques. Special emphasis is placed on refining two-stage detection algorithms to enhance both accuracy and efficiency. However, conventional methods like Part A2 encounter difficulties due to inadequate representation of point cloud data and neglect of target correlations. To address these challenges, an advanced 3D object detection methodology named the Multi-Method Fusion and Cascaded Attention Network (MMFCNet) is proposed. The MMFCNet enhances the capabilities of the M3DETR by incorporating multi-representation, multi-scale processing, and relationship modeling techniques to improve accuracy and resilience. Additionally, enhancements are made to the cascade attention network to prioritize feature importance and objectively extract valuable features from sparse and irregular point cloud data. By integrating different subnets and concern modules, this method improves the quality and detection accuracy of regional suggestions. Experiments on the KITTI dataset show that using a single RTX3090 GPU and dedicated LiDAR point cloud data can significantly improve performance. Notably, the method achieved 2.5%, 12.2%, and 1.1% improvements in all categories of moderate difficulty for the KITTI 3D inspection benchmark, respectively, thus validating the implementation of the advanced technology.</div>

<p>&nbsp;</p>

## Installation

See [installation instructions](INSTALL.md).

## Getting Started

See [Getting Started with MMFCNet](GETTING_STARTED.md).

# Acknowledgement

The source code of MMFCNet is based on [OpenPCDet](https://github.com/open-mmlab/OpenPCDet). 
