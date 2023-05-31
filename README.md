# VOCof-fasterrcnn-retinanet
faster-rcnn：模型地址：链接：https://pan.baidu.com/s/1iYaLKUZTIyKsydvNj4CDQw 
提取码：s6oq 
retinanet：链接：https://pan.baidu.com/s/14uoUfQEIhhycL7muh8X5XA 
提取码：hxin 
数据集：VOC数据集
训练过程：
1.Faster—RCNN
进行50个epoch的训练，主干网络为renet50，通过主干网络提取特征，然后通过rpn选出region proposal，最后经过ROIpooling后进行分类，回归
region proposal示图：

<img width="281" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/8b1f794f-0800-4ea3-894c-17905f104e02">




<img width="279" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/7ca4c9ec-0469-44d3-a34b-b54d17fa4b58">

最终分类预测：

<img width="415" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/d9087ea9-39a4-413e-8e67-09a71f21d052">




<img width="385" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/244bbc04-31a2-4635-8570-18eb7a0492ec">




<img width="416" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/de1875c8-fcd6-4701-ad51-1a51e0416fe6">

2.retinanet
one-stage目标检测模型，主干网络resnet50
训练结果：

<img width="269" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/e8be7382-8d80-4049-840b-211d67c55ace">




<img width="300" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/39706f61-5c35-4d01-83e9-b4ab8fbbe8f7">




<img width="272" alt="image" src="https://github.com/JoyTzuWon/VOCof-fasterrcnn-retinanet/assets/129930916/da338d38-ca6e-43f8-9fa9-7a42d4549d70">


Referrence：https://github.com/bubbliiiing/retinanet-keras/tree/bilibili
Referrence：https://github.com/bubbliiiing/faster-rcnn-pytorch/tree/bilibili
