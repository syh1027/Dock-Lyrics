# Dock Lyrics

**Keep lyrics in your Dock.**

[English](#english) · [简体中文](#简体中文) · [Download](https://github.com/syh1027/Dock-Lyrics/releases/latest) · [Report an issue](https://github.com/syh1027/Dock-Lyrics/issues)

## English

Dock Lyrics is a lightweight macOS app that displays two lines of synced lyrics over the Dock area. Follow your music while working or browsing, without keeping your music player's lyrics window open.

It uses space already reserved for a visible Dock. Lyrics disappear when playback pauses and step aside when your pointer approaches, so your apps remain easy to reach.

### Features

- **Four supported players:** Apple Music, NetEase Cloud Music, QQ Music, and Spotify. NetEase and QQ Music support includes their Mac App Store and website editions.
- **Two lyric layouts:** choose classic two-line lyrics or two lines that scroll upward as the song progresses.
- **Flexible alignment:** staggered center, left, or right alignment, with the lyric block kept centered over the Dock.
- **Fits your desktop:** adapts to the Dock's size and samples colors from the lower part of your wallpaper for the lyric bar's background.
- **Automatic visibility:** hides when playback pauses and yields when your pointer approaches the Dock.
- **Automatic lyric matching:** uses available local lyric data and online sources, including NetEase Cloud Music, QQ Music, and LRCLIB. Online lookups do not require those players to be installed.
- **Current song first:** prioritizes the song playing now. Background preparation of upcoming lyrics starts after the current lyrics are ready, when a supported queue is available.
- **Recovery and caching:** caches matched lyrics and makes a limited number of automatic retries after an initial lookup failure.
- **Timing controls:** adjust the lyric offset in Settings.
- **Chinese and English UI:** follows your system language by default, with a manual language selector. Chinese system languages use Simplified Chinese; all other system languages use English. Song titles and lyrics retain their original language.
- **Light and dark appearance:** the settings and running app icon follow the system appearance. Menu bar icons indicate whether the lyric overlay is active.
- **In-app updates:** check for updates from the app and install new versions without downloading another installer manually. Automatic checks are available through the updater's preferences and require access to the update service.

### Download and use

[Download the latest release](https://github.com/syh1027/Dock-Lyrics/releases/latest).

The universal build includes Apple Silicon and Intel binaries and requires macOS 13 or later. Open the DMG, drag Dock Lyrics into Applications, and launch it from there. Follow the permission prompts, then play a song in a supported player. Enable online lyrics in Settings if you want missing lyrics to be found online.

Dock Lyrics is designed primarily for a **visible Dock at the bottom of the screen**. Lyrics depend on the available sources and track metadata, so some songs may not have a match or may need a timing adjustment. Preparing upcoming lyrics depends on the player and queue access; Spotify queue preloading is not currently supported.

This is an independently distributed app and is not currently notarized by Apple. macOS may ask you to approve its first launch in System Settings → Privacy & Security.

### Feedback and project status

Bug reports and suggestions are welcome in [Issues](https://github.com/syh1027/Dock-Lyrics/issues). Include your macOS version, Dock Lyrics version, player, and steps to reproduce the problem. For lyric matching issues, add the song title and artist. Reports in English or Chinese are welcome; please leave out personal information and account credentials.

This repository provides product information and compiled releases. The application source code is not public. Dock Lyrics is an independent project and is not affiliated with Apple, NetEase, Tencent, or Spotify.

---

## 简体中文

**让歌词留在 Dock。**

Dock Lyrics 是一款轻量的 macOS 歌词应用，在 Dock 所在的位置显示两行同步歌词。工作、浏览网页时，也能跟上正在播放的音乐，无需一直打开音乐软件的歌词窗口。

它利用保持显示的 Dock 已经占用的空间。音乐暂停时，歌词自动隐藏；鼠标靠近时，歌词会让位，方便继续点击 Dock 中的应用。

### 功能

- **支持四款播放器：** Apple Music、网易云音乐、QQ 音乐和 Spotify；网易云音乐与 QQ 音乐支持 Mac App Store 版和官网版。
- **两种歌词样式：** 经典双行，以及随播放进度向上切换的滚动双行。
- **灵活的文字对齐：** 错落居中、左对齐和右对齐，歌词整体始终位于 Dock 中央。
- **融入桌面：** 跟随 Dock 尺寸调整显示区域，并参考壁纸底部的颜色设置歌词栏背景。
- **自动让位：** 暂停播放时隐藏歌词，鼠标靠近时让出 Dock，方便打开应用。
- **自动匹配歌词：** 使用可用的本机歌词数据和在线来源，包括网易云音乐、QQ 音乐及 LRCLIB。在线取词无需安装对应播放器。
- **优先加载当前歌曲：** 当前歌词就绪后，再根据可读取的播放队列，在后台准备后续歌曲的歌词。
- **缓存与自动恢复：** 缓存已匹配的歌词，首次查询失败时进行有限次自动重试。
- **同步微调：** 可在设置中调整歌词时间偏移。
- **中英文界面：** 首次使用默认跟随系统，也可手动选择。中文系统语言统一显示简体中文，其他系统语言显示英文；歌名与歌词保留原文。
- **浅色与深色外观：** 设置页及运行中的应用图标跟随系统明暗切换，菜单栏图标反映歌词栏的显示状态。
- **应用内更新：** 可直接检查、下载并安装新版本，无需重新手动下载安装包。更新组件提供自动检查选项，需要能够连接更新服务。

### 下载与使用

[下载最新版本](https://github.com/syh1027/Dock-Lyrics/releases/latest)。

通用安装包包含 Apple Silicon 与 Intel 二进制程序，要求 macOS 13 或更新版本。打开 DMG，将 Dock Lyrics 拖入 Applications 后，从应用程序文件夹启动。按照提示授予必要权限，再打开支持的播放器播放歌曲。如需在线补充缺失歌词，请在设置中开启“在线歌词”。

目前主要针对**位于屏幕底部、保持显示的 Dock**设计。歌词可用性和同步精度取决于曲目信息及来源，部分歌曲可能没有匹配结果，或需要微调时间偏移。下一首预加载取决于播放器及队列访问条件，目前不支持 Spotify 队列预加载。

应用通过独立渠道分发，目前尚未获得 Apple 公证。首次打开时，macOS 可能需要你在“系统设置 → 隐私与安全性”中允许启动。

### 反馈与项目状态

欢迎通过 [Issues](https://github.com/syh1027/Dock-Lyrics/issues) 提交问题或建议，中英文均可。请附上 macOS 版本、Dock Lyrics 版本、播放器和复现步骤；歌词匹配问题请另外提供歌名及歌手。请勿附上个人信息或账号凭证。

此仓库提供产品介绍与编译后的安装包，应用源码暂不公开。Dock Lyrics 是独立项目，与 Apple、网易、腾讯及 Spotify 没有隶属关系。

© 2026 SYH
