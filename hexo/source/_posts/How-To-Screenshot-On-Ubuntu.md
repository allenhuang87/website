title: 在ubuntu上截图
date: 2016-09-12 23:46:00
tags:
---
如何在不安装第三方工具的情况下，Ubuntu如何截图呢？这个问题一直困扰着我，今天终于找到一个不借用其他工具，使用Ubuntu系统自带的工具就可以完成截图了，这个工具就是gnome-screenshot。
先看帮助文档:
```
$ gnome-screenshot --help
Usage:
  gnome-screenshot [OPTION...]

Help Options:
  -h, --help                     Show help options
  --help-all                     Show all help options
  --help-gapplication            Show GApplication options
  --help-gtk                     Show GTK+ Options

Application Options:
  -c, --clipboard                Send the grab directly to the clipboard
  -w, --window                   Grab a window instead of the entire screen
  -a, --area                     Grab an area of the screen instead of the entire screen
  -b, --include-border           Include the window border with the screenshot
  -B, --remove-border            Remove the window border from the screenshot
  -p, --include-pointer          Include the pointer with the screenshot
  -d, --delay=seconds            Take screenshot after specified delay [in seconds]
  -e, --border-effect=effect     Effect to add to the border (shadow, border, vintage or none)
  -i, --interactive              Interactively set options
  -f, --file=filename            Save screenshot directly to this file
  --version                      Print version information and exit
  --display=DISPLAY              X display to use

```
说一下主要的选项
-a: 选择区域
-w: 选择窗口
-c: 直接拷贝到剪贴板
-f: 直接保存到文件
常用的就是这几项了，所以可以省去安装什么shullter之类的工具了，如果仅仅是截图的话，还是挺方便的。
