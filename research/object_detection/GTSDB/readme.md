## How to use
1. Download finetune(pre-trained model) from [Tensorflow detection model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)

### Some command might be used (_path need to be change_)
1. Run ‘train.py’:    python object_detection/train.py --logtostderr --train_dir=./object_detection/gtsd_train/ --pipeline_config_path=./object_detection/training/ssd_mobilenet_v1_coco.config
2. Run ‘eval.py’:     python object_detection/eval.py --logtostderr --pipeline_config_path=/workspace/notebook/hsi2018/ssd_mobilenet_v1_fddb.config --checkpoint_dir=/workspace/notebook/hsi2018/trained_fddb --eval_dir=/workspace/notebook/hsi2018/logs
3. Tensorboard: 
    1. tensorboard --logdir gtsb_train/
    2. URL: http://localhost:6006/
4. PYTHONPATH:     (py35_qt4) qing@qing-System-Product-Name:/media/qing/linux/repo/TF_detection_API/models/research$ export PYTHONPATH=$PYTHONPATH:`research`:`research`/slim



## Experimental result


These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```
