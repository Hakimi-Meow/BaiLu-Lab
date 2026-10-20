# 白露桌宠 · 电脑版

Windows x64 单文件，免安装。

## 下载

- 版本页：https://github.com/Hakimi-Meow/BaiLu-Lab/releases/tag/pc-v1.01
- 直链：https://github.com/Hakimi-Meow/BaiLu-Lab/releases/download/pc-v1.01/BaiLuPet-v1.01.exe

首次运行若弹 SmartScreen，点「更多信息 → 仍要运行」。
存档：`%APPDATA%\BaiLuPet\state.json`

## 功能

- 透明无边框悬浮，可拖动
- 点击冒气泡说话，右键菜单
- 摸摸头 / 喂点东西 / 看状态 / 看电脑
- 大小三档、总在最前、整点报时、开机自启
- 托盘图标、双击召唤
- 养成存档：好感 / 饱食 / 心情，离线也会结算
- 本地 CPU / 内存 / 网速，不联网
- 性能模式：默认不晃动，全屏游戏时自动隐身

## 版本记录

| 版本 | 说明 |
| --- | --- |
| 1.0 | 首个版本 |
| 1.01 | 修气泡文字被截断；修开启后掉帧（默认关待机动画、全屏自动隐身、降低动画频率、合并定时器） |

## 构建

源码在作者本地用 .NET 8 交叉编译（Linux arm64 → win-x64），
命令与注意事项见仓库外的构建笔记。
