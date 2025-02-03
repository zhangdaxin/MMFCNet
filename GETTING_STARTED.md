# Getting Started
Please see [Getting Started with OpenPCDet](https://github.com/open-mmlab/OpenPCDet/blob/master/docs/GETTING_STARTED.md) for full usage.


### Inference with Pre-trained Models

1. Pick a configuration file and its corresponding model from
  [model zoo](MODEL_ZOO.md),
  for example, the config file of ./tools/cfgs/m3detr_models/m3detr_waymo_1500.yaml.

2. We provide `./scripts/dist_test.sh` that is able to test with a pretrained model. Run it with:
```
cd tools/
sh ./scripts/dist_test.sh 1 --cfg_file ./cfgs/m3detr_models/m3detr_waymo_1500.yaml --workers 4 --ckpt /path/to/checkpoint_file --eval_tag test_out --batch_size 8 --save_to_file [--other-options]
```

### Train a Model
We provide `./scripts/dist_train.sh` that is able to train a model with the specified config file. Run it with:
```
cd tools/
sh ./scripts/dist_train.sh 1 --cfg_file ./cfgs/m3detr_models/m3detr_waymo_1500.yaml --workers 4
```
For more options, see ./scripts/dist_train.sh.
