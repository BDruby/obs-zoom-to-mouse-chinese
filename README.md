# obs-zoom-to-mouse-chinese
本项目灵感基于:
https://github.com/BlankSourceCode/obs-zoom-to-mouse
由于这个项目好像暂停维护了，新版本的OBS无法使用，所以便再此基础上做了针对最新版本API的修改和优化，以及提供了汉化版本

# 使用说明：

# OBS Zoom to Mouse

一个OBS Lua脚本，可以缩放显示捕获源以聚焦鼠标位置。

## 功能特性

- 将显示捕获源缩放到鼠标位置
- 支持自动跟随鼠标移动
- 可调节缩放级别和速度
- 跨平台支持（Windows, Linux, macOS）
- 热键控制缩放功能

## 安装方法
### 以中文版为例

1. 将 `obs-zoom-to-mouse-chinese.lua` 或 `obs-zoom-to-mouse-en.lua` 文件复制到OBS的脚本目录中
通常地址为：obs-studio\data\obs-plugins\frontend-tools\scripts
也可以放入其他路径
2. 打开OBS，转到"工具" → "脚本"
3. 点击"浏览"按钮，选择脚本文件
4. 从下拉菜单中选择要缩放的显示捕获源
5. 点击“文件” → “设置” → “快捷键” 找到“切换鼠标缩放（控制缩放大小）”“切换缩放时鼠标跟随（开关鼠标的跟随功能）”

## 使用说明

- 选择要缩放的显示捕获源
- 设置缩放级别（默认为2倍）
- 启用/禁用自动跟随鼠标选项
- 使用热键快速切换缩放功能
- 根据需要调整跟随速度和边框设置

## 配置选项

- **缩放源**: 选择要缩放的显示捕获源
- **缩放级别**: 设置缩放倍数
- **缩放速度**: 设置缩放动画的速度
- **跟随速度**: 设置鼠标跟随的平滑度
- **跟随边框**: 设置鼠标移动的边框距离
- **自动跟随鼠标**: 启用/禁用自动跟随功能
- **手动源位置**: 手动设置源的位置和大小参数

## 平台兼容性

- **Windows**: 支持monitor_capture源
- **Linux**: 支持xshm_input源
- **macOS**: 支持screen_capture/display_capture源

## 故障排除

- 如果缩放功能不工作，请确保选择了正确的显示捕获源
- 对于非显示捕获源，请启用"设置手动源位置"选项
- 检查是否存在与其他裁剪滤镜的冲突

## 许可证

Copyright (c) BDruby. All rights reserved.
