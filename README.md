# ARB (Amazing-Right-Button)

Windows 10 鼠标右键手势工具，极大提升鼠标操作下的多任务体验。通过鼠标右键的手势，轻松使用Windows10的虚拟桌面和多任务控制。

> 应用场景：如果你感觉桌面窗口太多太乱，轻松划一下鼠标，整理一下桌面和窗口，心情好多了！

---

## 安装说明

### 傻瓜化安装

直接运行dist目录下的.exe格式文件，即可立即使用。

### 开发者安装

1. 点击右上角的绿色按钮【clone or download】，点击【Download ZIP】，下载整个压缩包；
2. 在本地解压，打开runtime文件夹里的auto-hot-key-runtime.exe文件，安装环境。
3. 打开src目录下的.ahk文件，即可立即使用。

## 使用说明

首先：新建虚拟桌面，按下 Ctrl + Win + D 即可新建一个虚拟桌面！

1. 脚本总开关（注意看任务栏图标变化）：ALT + Win + P
2. 按住鼠标右键同时左右滑动：切换虚拟桌面
3. 按住鼠标右键同时向上滑：切换显示任务视图
4. 按住鼠标右键同时向下滑：切换显示桌面。
5. 查看帮助说明：ALT + Win + H

## 开机自启动

1. 按Win+R；
2. 输入:`shell:startup`
3. 点击确定，系统会打开"启动文件夹"；
4. 将.ahk或者.exe文件复制进这个文件夹，即可开机自启动。

## 贡献代码

1. 打开解压后**auto-hot-key-runtime.exe**文件，安装AHK环境；
2. 阅读[AHK文档](http://ahkcn.sourceforge.net/docs/Tutorial.htm)
3. 新建分支，编辑ahk脚本；
3. 运行ahk脚本进行调试，调试时，右键任务栏图标，点击reload即可重载脚本；
4. 开发完成后提交Pull Request。

## 关于

兼容性：本脚本只兼容Windows 10操作系统。

源码：<https://github.com/hansenwangvip/Amazing-Right-Button>

本软件由[AutoHotKey](http://ahkcn.sourceforge.net/docs/Tutorial.htm)编写，代码开源，保证无毒，放心享用。

---
