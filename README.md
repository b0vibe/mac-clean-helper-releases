# Mac 清洁助手 / Mac Clean Helper

**清洁 MacBook 键盘、触控板和屏幕时，临时禁用相应输入，防止擦拭过程中误按按键、误点内容、拖动文件或触发快捷键。**

擦键盘时很容易输入文字或触发快捷键，擦触控板时可能产生点击和拖动。Mac 清洁助手让你先选择要清洁的区域，再临时拦截对应输入，让设备可以安心擦拭。清洁结束后，键盘和触控板会恢复正常使用。

Mac Clean Helper temporarily blocks keyboard or pointer input while you clean a MacBook, preventing accidental typing, clicks, drags, and keyboard shortcuts.

> **最新版本 / Latest release：[`v0.2.2`](https://github.com/b0vibe/mac-clean-helper-releases/releases/tag/v0.2.2)**

## 它能解决什么问题

- **键盘清洁**：临时拦截按键，避免擦拭键帽时输入文字、触发快捷键或操作当前应用；鼠标和触控板仍可用于结束清洁
- **触控板清洁**：临时拦截触控板和鼠标点按，避免擦拭时误选、误拖动或打开内容；按 `ESC` 或 `Q` 即可结束
- **屏幕清洁**：在 MacBook 内置显示屏上显示深色清洁画面并隐藏指针，让灰尘、油渍和指纹更容易看清；按任意键或点按即可退出

每次清洁最长 5 分钟。手动退出、计时结束、应用退出、电脑睡眠或用户会话切换时，应用都会结束清洁并恢复输入。

## 下载与安装

1. 前往 [Releases](https://github.com/b0vibe/mac-clean-helper-releases/releases) 下载 `Mac-Clean-Helper-v0.2.2-macOS-arm64.zip`
2. 使用同一 Release 中的 `SHA256SUMS.txt` 核对文件
3. 解压 ZIP，将“Mac 清洁助手”拖入“应用程序”文件夹
4. 打开应用，并按引导授予 macOS“辅助功能”权限

> GitHub 自动生成的 `Source code (zip)` 和 `Source code (tar.gz)` 只包含本公开仓库的说明文档，不是应用安装包，也不包含应用源代码

## 系统要求

- Apple Silicon Mac
- macOS 13 或更高版本
- 键盘和触控板清洁需要 macOS“辅助功能”权限

当前不支持 Intel Mac、Mac App Store 安装和自动更新。

## 为什么需要辅助功能权限

键盘和触控板清洁需要在清洁期间临时拦截输入，因此必须获得 macOS“辅助功能”权限。应用不会记录、保存或上传按键和点击内容。

## 隐私与安全

- 输入事件只在本机内存中即时处理
- 不记录、不保存、不上传按键或点击内容
- 当前版本不联网，不包含广告、分析或崩溃上报 SDK
- 清洁会话最长 5 分钟，并在退出、超时、睡眠和会话切换时自动恢复

完整说明：[隐私说明](PRIVACY.md) · [安全反馈](SECURITY.md) · [更新记录](CHANGELOG.md)

## English

Mac Clean Helper is a native macOS utility for safely cleaning a MacBook keyboard, trackpad, and screen. It temporarily blocks the relevant input while you wipe the device, preventing accidental typing, clicks, drags, and keyboard shortcuts.

### Cleaning modes

- **Keyboard cleaning:** blocks key input while pointer input remains available; click “End Cleaning” when finished
- **Trackpad cleaning:** blocks trackpad and mouse clicks while keyboard input remains available; press `Escape` or `Q` to finish
- **Screen cleaning:** shows a dark cleaning view on the built-in display and hides the pointer so dust and fingerprints are easier to see; press any key or click to exit

Every cleaning session is limited to five minutes. Input is restored on manual exit, timeout, app termination, sleep, or user-session change.

### Requirements and installation

Mac Clean Helper requires an Apple Silicon Mac running macOS 13 or later. Download `Mac-Clean-Helper-v0.2.2-macOS-arm64.zip` from [Releases](https://github.com/b0vibe/mac-clean-helper-releases/releases), verify it with `SHA256SUMS.txt`, extract it, and move the app to Applications.

Keyboard and trackpad cleaning require macOS Accessibility permission so the app can temporarily intercept input. The app does not record, store, or upload keystrokes or click contents. It makes no network connections and contains no advertising, analytics, or crash-reporting SDKs.

Copyright © 2026 b0vibe. The application is free to download for personal evaluation but is not open source. See [Copyright and use terms](LICENSE.md).
