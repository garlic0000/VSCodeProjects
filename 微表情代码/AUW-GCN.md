# AUW-GCN

项目github地址：  
[xjtupanda / AUW-GCN](https://github.com/xjtupanda/AUW-GCN)

项目环境配置：  
> OS: Ubuntu 20.04.4 LTS  
> Python: 3.8  
> Pytorch: 1.10.1  
> CUDA: 10.2, cudnn: 7.6.5  
> GPU: NVIDIA GeForce RTX 2080 Ti  

这个环境有点问题
1.配置CUDA10.2，在Ubuntu系统上配置，官网上只提供Ubuntu18.04  
2.这里pytorch为1.10.1，但在requirements.txt中torch版本为1.13.1

实际实验环境配置：

1.kaggle
误打误撞，环境配置成功过，但是再也没法复现  

a.python3.8 torch==1.13.1 torchvision==0.11.2+cu102
报错：需要python3.8以上 匹配不到torchvision==0.11.2+cu102

b.python3.9 torch==1.13.1 torchvision==0.11.2+cu102
报错：需要python3.9以上 匹配不到torchvision==0.11.2+cu102

c.python3.10 torch==1.13.1 torchvision==0.11.2+cu102

2.colab
服务器连接不稳定
没有conda环境
