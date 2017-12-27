# Deeplab v2 ResNet for Semantic Image Segmentation 

* [DeepLab-V1&V2](https://github.com/alisure-ml/FCN-Review/blob/master/DeepLab-V1%26V2.md)


### Pre-trained
The deeplab pre-trained ResNet-101 ckpt files (pre-trained on MSCOCO) are provided 
by DrSleep -- [here](https://drive.google.com/drive/folders/0B_rootXHuswsZ0E4Mjh1ZU5xZVU).


### Run 

* 训练/测试/预测
    ```
    python main.py --option=train
    python main.py --option=test
    python main.py --option=predict
    ```
    
* 多尺度（0.5， 0.75， 1.0）
    ```
    python main_msc.py --option=train
    python main_msc.py --option=test
    python main_msc.py --option=predict
    ```

### Reference

* [zhengyang-wang/Deeplab-v2--ResNet-101--Tensorflow](https://github.com/zhengyang-wang/Deeplab-v2--ResNet-101--Tensorflow)
