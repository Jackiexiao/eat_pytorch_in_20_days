# 六、Pytorch的高阶API

Pytorch没有官方的高阶API。一般通过nn.Module来构建模型并编写自定义训练循环。

为了更加方便地训练模型，作者编写了仿keras的Pytorch模型接口：torchkeras， 作为Pytorch的高阶API。

本章我们主要详细介绍Pytorch的高阶API如下相关的内容。

* 构建模型的3种方法(继承nn.Module基类，使用nn.Sequential，辅助应用模型容器)

* 训练模型的3种方法(脚本风格，函数风格，torchkeras.Model类风格)

* 使用GPU训练模型(单GPU训练，多GPU训练)


如果对本书内容理解上有需要进一步和作者交流的地方，欢迎在公众号"Python与算法之美"下留言。作者时间和精力有限，会酌情予以回复。

也可以在公众号后台回复关键字：**加群**，加入读者交流群和大家讨论。

![image.png](../data/Python与算法之美logo.jpg)
