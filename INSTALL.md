## Installation

### Requirements
- Linux with Python ≥ 3.6
- PyTorch ≥ 1.1. Please check PyTorch version matches that is required by OpenPCDet.
- OpenPCDet: follow [OpenPCDet installation instructions](https://github.com/open-mmlab/OpenPCDet/blob/master/docs/INSTALL.md).


### Example conda environment setup
```bash
conda create -n mmfcnet python=3.6 -y
conda activate mmfcnet
conda install pytorch=1.6.0 torchvision cudatoolkit=10.2 -c pytorch
pip install spconv-cu102
pip install tqdm scipy scikit-image
git clone https://github.com/zhangdaxin/MMFCNet.git
cd mmfcnet
python setup.py develop
```
### For newer version of CUDA
```
conda create -n mmfcnet python=3.6 -y
conda activate mmfcnet
conda install pytorch=1.9.1 torchvision cudatoolkit=11.1 -c pytorch -c nvidia
pip install spconv-cu113	
pip install pyyaml numba llvmlite tensorboardX SharedArray easydict tqdm scipy scikit-image imageio
git clone https://github.com/zhangdaxin/MMFCNet.git
cd mmfcnet
python setup.py develop
```
