<h1 align="center">
  Gnome Bing锁屏
</h1>

[English](https://github.com/zhangzp9970/GnomeBingLockScreen/blob/master/README.md) | [中文](https://github.com/zhangzp9970/GnomeBingLockScreen/blob/master/README-zh-cn.md)

> 一个将必应美图设置为GNOME锁屏壁纸的小python脚本 

## 你有没有对GNOME每天相同的锁屏壁纸感到厌烦？
## 你有没有希望有一个类似于Windows Spotlight的锁屏壁纸在你的GNOME桌面上？
## 这个项目正是起源于这样的想法。
## 现在已经有一个相似且更加好的项目，详见https://github.com/neffo/bing-wallpaper-gnome-extension 但是，用python 重写一个对我来说是一个很好的锻炼机会，因此我会持续把这个项目做的更加完善

## 特点
* 每天通过必应美图更新GNOME锁屏
* 下载到的图片被放在 ~/Pictures/Bing/ 目录下
* 首次运行自动生成一个配置文件在~/.config/Bing/目录下
* 删除超过７天的图片(有待完善)
  
## 待完成
* 增加一个图形化配置界面
* 增加依赖库
* 使用Qt完善或者去除程序对于python的依赖性
* 寻找Linux的API来完成设置操作，而非调用gsettings命令
* 制作一个pip安装包
* 增加ystemd service文件
  
## 使用方法
克隆这个仓库然后在启动文件里添加 python3 bing_screen_saver.py 

## 屏幕截图
![lock](/img/Screenshot.png)
## License
GNU General Public License v3

Copyright (C) 2018 by 张泽平 <zhangzp9970@outlook.com>

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

![gpl](/img/GPLv3_Logo.png)