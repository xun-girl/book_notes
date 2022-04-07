---
title:  LaTeX环境搭建
date: 2022-1-14 13:22:22
tags: LaTeX
img: https://s2.loli.net/2022/01/24/5bsiCMYNPnEo8kS.png
categories:
- 技术
---
# 前言

介绍一下关于`LATEX`软件的安装，如果仅仅是想快速上手latex的朋友，可以直接用在线的LaTeX编辑器——[Slager](https://slager.cn/Home#/home)

# 正文

##   LaTeX+TeXstudio

首先安装`tex`环境，我这里选用的环境是`TeX Live`，如果您想了解 `TeX Live `和`MiKTeX `的区别，可以查看此篇文章：

[Tex Live和MikTex的对比](https://link.zhihu.com/?target=https%3A//www.cnblogs.com/liuliang1999/p/12656706.html)

### （一）下面安装**Tex Live**环境

通过此[链接]([Acquiring TeX Live as an ISO image - TeX Users Group (tug.org)](https://tug.org/texlive/acquire-iso.html))下载Tex Live

<img src="C:\Users\张家驹\AppData\Roaming\Typora\typora-user-images\image-20220124125116294.png" alt="image-20220124125116294" style="zoom: 50%;" />

通过点击上方的 **download from a nearby CTAN mirror**后跳转到

<img src="C:\Users\张家驹\AppData\Roaming\Typora\typora-user-images\image-20220124125501124.png" alt="image-20220124125501124" style="zoom: 50%;" />

往后可能会更新，所以不必在意Data,只是不同版本号的发行日期，选中第二个或者第三个(texlive.iso)点击即可下载，下载时间比较漫长

1000 years later....

下载好后，点击打开文件

<img src="https://s2.loli.net/2022/01/24/tR4fAuQVx9IjDhZ.png" alt="image-20220124130216571" style="zoom: 67%;" />

找到  框选的文件，并鼠标右击-----以管理员身份运行

<img src="C:\Users\张家驹\AppData\Roaming\Typora\typora-user-images\image-20220124130403333.png" alt="image-20220124130403333" style="zoom: 50%;" />

这时候会跳转出这个画面

<img src="https://s2.loli.net/2022/01/24/eNLmFciEBAdSy38.png" alt="image-20220124130536294" style="zoom: 50%;" />

ps:出现了一个警告符号，不用担心没出错，点击确定就消失了

然后出现了一个Tex Live的安装程序，点击**Advanced**可以得到详细的安装目录等等，都可以自行更改，建议除了安装位置外别的都不要动，完事后点安装即可进行，安装过程很久，耐心等待......

### 补充

补充一个地方，有很多朋友在安装的时候卡住了（和我一样），并且出现了；

> open(>C:\Users\ít\x{00b8}\x{00e7}\AppData\Local\Temp\QjIci8zRzB\oCNhxg3WmZ/texlive.infra.win32.r57932.tar.xz) failed: No such file or directory at E:/download/texlive2021/tlpkg/TeXLive/TLUtils.pm line 1220, <STDIN> line 100.

这样类似的提示，这里是**环境变量**的方面的问题,有现成的文章，已经找好了，[链接]([(45条消息) 关于texlive2021安装，一直卡在安装界面怎么回事?_laixiangwei的博客-CSDN博客_texlive安装卡住不动了](https://blog.csdn.net/laixiangwei/article/details/121135357))处理好之后就可以顺利的安装了

2000 years later.....

安装好之后，latex环境已经内置到您的计算机中

### （二）安装 TeXstudio

直接在官网下载 https://link.zhihu.com/?target=http%3A//texstudio.sourceforge.net/

登到官网后 点击中间那个 **Download now**,就开始下载了，

下载好后 直接打开

<img src="https://upload-images.jianshu.io/upload_images/5714082-b25bd4b5702af628.png?imageMogr2/auto-orient/strip|imageView2/2/w/854/format/webp" style="zoom: 80%;" />

可以先将界面更改成中文，点击上方的`options`->`Configure TeXstudio`，在弹出来的对话框中更改`Language`为`zh_CN`

<img src="https://upload-images.jianshu.io/upload_images/5714082-1fa34b9cf2e3070c.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp" style="zoom: 80%;" />

如果要书写中文文档，点击：选项——设置——构建——默认编译器——选择**XeLaTex**

<img src="https://s2.loli.net/2022/01/24/isTrf2nWYNRZQA4.png" alt="image-20220124132747174" style="zoom: 50%;" />

至此 就可以在TeXstudio中进行Latex格式论文的编写了

q
