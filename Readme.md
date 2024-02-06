# Taichi Study Notes by an Idiot 

## 什么是 Taichi?

[Taichi 是一种嵌入 Python 中的特定领域语言，可帮助您轻松编写可移植的高性能并行程序。](https://www.taichi-lang.org/) 

## 安装 Taichi

安装参考的是这个 [知乎专栏](https://zhuanlan.zhihu.com/p/570625967)

事先声明，我比较小白，很多工具都只是会用一点点。我正在使用Anaconda管理我的python环境（然而Taichi001是我的第一个base以外的环境.jpg）

Taichi似乎不在conda包含的包以内，无法用`conda install taichi`下载，必须通过`pip install taichi`下载。在切换激活环境后，下载的包不会在别的环境中下载。

我使用的是清华镜像源，不知道是不是因为这几天魔法的效果不是很好，使用`pip install taichi`下载了三次都中断了。然后我找了Taichi的[安装疑难解答](https://docs.taichi-lang.org/zh-Hans/docs/install/)，把
```pip install taichi```
改为了
```pip install taichi -i https://pypi.douban.com/simple```
就很快安装完成了

## Taichi 的一些学习资料
- Taichi官方的Guide和doc[https://docs.taichi-lang.cn/docs/hello_world/]
- Taichi官方的课程：[太极图形课-第一季](https://docs.taichi-lang.org/tgc01)

