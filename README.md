# RefIndoor
RefIndoor: An RGB-D Visual Grounding Dataset with Clutterred Indoor Scenes for Robotics.

[Homepage](https://luyh20.github.io)


## Download the RefIndoor Dataset

You can download **RefIndoor** [here](https://drive.google.com/uc?export=download&id=1-kEfagTovmcbEFG6-C_xatZfFiLWQmiU) or [Google Drive](https://drive.google.com/file/d/1-kEfagTovmcbEFG6-C_xatZfFiLWQmiU/view?usp=sharing).
The data directories should like this:

```
RefIndoor/
├── data/
│   └── final_dataset/
│       ├── train
│       ├── testA
│       └── testB
```


## RefTR Model for RefIndoor

The RefTR model is from https://github.com/ubc-vision/RefTR.

### Requirements

References：
```shell
python=3.6.13
torch=1.8.0+cu111
torchvision=0.9.0+cu111
torchaudio=0.8.0
```

And others:
```shell
pip install -r requirements.txt
```

### Training and Evaluation

Training:
```shell
sh train_refindoor.sh
```

Evaluation：
```shell
sh test_refindoor.sh
```

### Model Zoo

You can download the models with ResNet-50 backbone and ResNet-101 backbone in [here](https://drive.google.com/uc?export=download&id=1P3TRJhM0DYZxeZtpY4kYFi9iX6AGh1u3). These models take RGB images as input. 


