# Beneath the Sink

**Windows 64-bit · English / 简体中文** · [中文介绍](#简体中文)

An educational exploration game about microorganisms, designed for young audiences. Begin at a kitchen sink, venture into a blue underwater pipe network, meet its microscopic inhabitants, and explore through dialogue, short bursts of movement, and flowing water.

![English title screen](images/title.png)

## Download

**[Download the latest release](https://github.com/hotcatmiaomiaomiao-arch/Beneath-the-Sink/releases/latest)**

Download `BeneathTheSink-Windows-v3.zip` from the release **Assets**, extract the entire archive, and run `Beneath the Sink.exe`. Keep the `Engine` and `Microorganism` folders alongside it. Unreal Engine is not required.

The automatically generated **Source code (zip/tar.gz)** archives contain this repository's documentation, not the playable game.

## Controls

For kitchen controls, see **How to Play** on the title screen. In the pipe level:

| Key | Action |
| --- | --- |
| W / A / S / D | Move |
| Space | Ascend |
| Ctrl | Descend |
| Shift | Short burst; pass through slime barriers |
| F | Advance or finish dialogue |
| Esc | Quit the game |

Choose English or Chinese on the title screen. At the end, restart the game or return to the main menu.

![English in-game dialogue](images/gameplay.png)

## Troubleshooting

- If the Microsoft Visual C++ runtime is missing, run `Engine/Extras/Redist/en-us/vc_redist.x64.exe` inside the game folder.
- If the default DirectX 12 mode cannot start, try `Compatibility Mode.bat`. It uses DirectX 11, so lighting may differ.
- Report issues with the game version, system information, reproduction steps, and a screenshot.

## About this repository

This repository hosts the game description and playable Windows releases. The editable Unreal project, Blueprints, and original art assets are not published here. This is not an open-source game release.

Third-party audio and font notices are included in the game's `Licenses` folder and remain governed by their respective licenses.

Created by [hotcatmiaomiaomiao-arch](https://github.com/hotcatmiaomiaomiao-arch). Built with Unreal Engine 5.6.

---

## 简体中文

### 水槽之下

一款面向青少年的微生物科普探索游戏。从厨房水槽出发，进入蓝色的水管世界，认识不同微生物，穿过污膜、借助水流，探索水槽之下的微观世界。

### 下载

**[下载最新版](https://github.com/hotcatmiaomiaomiao-arch/Beneath-the-Sink/releases/latest)**

在 Releases 的 **Assets** 中下载 `BeneathTheSink-Windows-v3.zip`，完整解压，再运行 `Beneath the Sink.exe`。请保留旁边的 `Engine` 和 `Microorganism` 文件夹，不要只移动 EXE。无需安装 Unreal Engine。

GitHub 自动生成的 **Source code (zip/tar.gz)** 只有本仓库的介绍文件，不是游戏安装包。

### 操作

厨房场景的操作请查看游戏开始界面的操作说明。水管场景：

| 按键 | 操作 |
| --- | --- |
| W / A / S / D | 前后左右移动 |
| Space | 上升 |
| Ctrl | 下降 |
| Shift | 短暂加速、穿过污膜 |
| F | 继续或结束对话 |
| Esc | 退出游戏 |

在开始界面可切换中文和英文。结束后可重新开始，或返回主菜单。

### 启动问题

- 缺少 Microsoft Visual C++ 运行库：运行游戏文件夹内的 `Engine/Extras/Redist/en-us/vc_redist.x64.exe`。
- 默认 DirectX 12 模式无法启动：尝试 `Compatibility Mode.bat`（DirectX 11，画面可能略有差别）。
- 发现问题时，请在本仓库 Issues 中附上游戏版本、系统信息、问题描述和截图。

### 关于本仓库

这是游戏成品的介绍与下载仓库。这里只提供编译后的 Windows 游戏，不公开可编辑的 Unreal 工程、蓝图或原始美术资源。

游戏内第三方音效、字体的来源和授权说明随下载包的 `Licenses` 文件夹提供；各自授权继续适用。

作者：[hotcatmiaomiaomiao-arch](https://github.com/hotcatmiaomiaomiao-arch)。使用 Unreal Engine 5.6 制作。
