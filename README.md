# Tianchi2021 队伍：嘿嘿嘿
## 解决方案
最终结果融合了，hrnet32，hrnet48，hrnet32的轻量版，danet-res50，pspnet-res50，danet-res101等的一些模型结果
融合方式为，对各个模型输出的logits进行相加。
## 环境
python 3.6.12  
torch 1.6  
cuda 10.2  
其他使用到的包安装最新版本即可
## 复现流程
### 复现B榜结果
```
sh test.sh
```
### 重新训练，复现权重
```
sh train.sh
```
但是由于模型较多，复现难度较大，默认的train.sh可以复现一个40.1的A榜精度
