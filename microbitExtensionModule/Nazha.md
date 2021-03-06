# 14.哪吒扩展板

## 14.1.简介
哪吒是一款全能型的micro:bit扩展板。板载4路舵机驱动，4路电机驱动，7路传感器扩展接口；传感器接口均采用RJ11接头，防呆防反插，方便学生们在课堂上快速准确连线；外壳设有乐高和慧鱼结构件兼容接口，可将电子模块与主流结构件结合起来，方便学生们搭建个性化的micro:bit创意编程作品。

![](./images/03444_01.png)

## 14.2.特性
---
- RJ11端口设计，防止误插，易于使用。
## 14.3.技术规格
---

![](./images/03444_02.png)


## 14.4.外形与定位尺寸
---


![](./images/03444_03.png)


## 14.5. 主要模块介绍
---

![](./images/03444_04.png)

## 14.6.添加专属扩展库
---

在MakeCode的代码抽屉中点击“高级”，查看更多代码选项。

![](./images/03444_05.png)

为了给WiFi模块编程，我们需要添加一个扩展库。在代码抽屉底部找到“扩展”，并点击它。这时会弹出一个对话框，搜索”https://github.com/elecfreaks/pxt-nezha“，然后点击下载这个代码库。

![](./images/03444_06.png)

*注意：*如果你得到一个提示说一些代码库因为不兼容的原因将被删除，你可以根据提示继续操作，或者在项目菜单栏里面新建一个项目。

## 14.7. 使用方法

### TT马达使用案例

![](./images/03444_07.png)

### 如图所示编写程序


![](./images/03444_08.png)


### 参考程序
请参考程序连接：[https://makecode.microbit.org/_8g40hhK9rLvW](https://makecode.microbit.org/_8g40hhK9rLvW)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_8g40hhK9rLvW" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---
### 结果
按键A按下时两个电机一起转动，当按键B按下时接在M1接口的电机停止转动，当按键A和B同时按下时两个电机同时停止转动。


### 舵机使用案例

![](./images/03444_09.png)

### 如图所示编写程序


![](./images/03444_10.png)


### 参考程序
请参考程序连接：[https://makecode.microbit.org/_L8rfzu3ELEyg](https://makecode.microbit.org/_L8rfzu3ELEyg)

你也可以通过以下网页直接下载程序，下载完成后即可开始运行程序。

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_L8rfzu3ELEyg" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---
### 结果
按键A按下时180°舵机转动到角度0°，按键B按下时360°舵机以100％转动。

