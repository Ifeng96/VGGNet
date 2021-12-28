# CIFAR100数据集

# 安装依赖库

```
pip install -r requirements.txt
```



# 训练

命令行执行
```
python train.py -net vgg16 -gpu
```



# 测试

命令行执行

```
python test.py -net vgg16 -weights path_to_vgg16_weights_file
```



注意：vgg16也可以换成vgg11 / vgg13 / vgg19