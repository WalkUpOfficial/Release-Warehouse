# System32 New Version Report

**Added `OnSystemtray` function. You can Use this function to add program to System tray.**

> **新增 `OnSystemtray` 函数。你可以使用该函数将程序添加到系统托盘。**

Function introduction:
Supports custom tray hover title, right-click menu dictionary configuration, custom exit callback function.
The left mouse button has three working modes:

1. Set left_button="Auto": Left click will pop up the right-click menu.
2. Pass a function to left_button: Execute this function directly when left-clicking the tray icon.
3. Pass a dictionary to left_button: Left click will pop up an independent menu separated from the right menu.

> 函数介绍：
> 支持自定义托盘悬浮提示文字、右键菜单字典式配置、自定义退出回调函数。
> 鼠标左键拥有三种工作模式：

1. 设置 left_button="Auto"：左键点击弹出右键菜单。
2. 给 left_button 传入函数：左键点击托盘图标时直接执行该函数。
3. 给 left_button 传入字典：左键点击弹出一套独立菜单，与右键菜单互相分离。

Extended description:
This function is built based on pystray. It runs the program in the background silently after minimizing, and provides flexible mouse click event handling.
All menu items use dictionary format: key = menu display text, value = callback function.
You can easily build resident background programs, such as system monitors, automatic tools and voice assistants.

> 扩展说明：
> 该函数基于 pystray 构建，程序最小化后可在后台静默常驻，并且提供灵活的鼠标点击事件处理。
> 所有菜单采用字典格式配置：键 = 菜单显示文字，值 = 回调函数。
> 你可以轻松搭建后台常驻程序，例如系统监控器、自动化工具、语音助手。
