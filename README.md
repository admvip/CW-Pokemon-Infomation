# CW Pokemon Infomation
![CW Pokemon](https://images.gitee.com/uploads/images/2021/0623/160208_6206ada7_8042044.jpeg "APP启动画面2.jpg")
## 介绍
#### CW Pokemon Mini(Pro) 升级固件及用户手册
#### CW Pokemon Mini(Pro) Updates firmware and user manual

## 软件架构
#### 升级包 ---- 内含升级所需的固件包、资源包等，固件包属于每次升级必须刷新的文件（升级包内所有文件名不得自行更改）；资源包根据每次的升级说明，选择刷新。

#### 工具包 ---- 内含图片生成器，用于用户自定义图片转码；PC和手机版串口程序，用于控制CW Pokemon发送中英文电码。


## 固件升级教程
#### 1.  按住F1和F4键的同时开机，LED亮后松开按键；
#### 2.  确认屏幕显示升级提示信息，如果没有升级信息，请重复步骤1操作；
#### 3.  使用数据线连接设备到电脑，电脑提示发现一个名为HAM MODULE的移动存储设备;
#### 4.  根据升级包的说明，将相应的文件复制移动存储设备中，一次只能复制一个文件，复制下一个文件前，需要长按F4使得移动存储设备复位一次，然后再继续复制其它的升级文件(文件名不得擅自更改)；
#### 5.  所需升级文件复制完毕后，长按电源键或者使用细针按压复位孔内的复位键关闭设备，等待3-5秒后重启设备，完成升级工作。


## 自定义开机画面的制作和刷新
![Software Setting](https://images.gitee.com/uploads/images/2021/0623/152311_eb572a02_8042044.png "QQ截图20210623152233.png")
####     用户可以通过升级固件的方法更换系统启动画面。打开工具包文件夹，解压Image2Lcd.rar并运行，按图设置参数，点击保存按钮生成图片的bin文件，将bin文件改名为F000000.bin。然后按固件升级的步骤，将F000000.bin文件刷新到设备中即完成自定义开机画面的更新操作。


![CW Pokemon](https://images.gitee.com/uploads/images/2021/0623/202226_72916e0c_8042044.jpeg "icon.jpg")
