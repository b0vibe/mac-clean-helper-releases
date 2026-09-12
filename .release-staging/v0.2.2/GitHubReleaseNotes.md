# Mac 清洁助手 v0.2.2 / Mac Clean Helper v0.2.2

正式版本 `0.2.2`，构建号 `8`

Production release `0.2.2`, build `8`

Mac 清洁助手用于在擦拭 MacBook 时临时拦截键盘或触控板输入，避免误按、误点和快捷键操作；屏幕清洁模式通过深色画面帮助看清灰尘和指纹。

Mac Clean Helper temporarily blocks keyboard or pointer input while cleaning a MacBook, preventing accidental typing, clicks, and shortcuts. Its dark screen-cleaning view makes dust and fingerprints easier to see.

## 本版本内容 / What’s included

- 全面调整首页、说明弹窗和清洁过程界面
- 清洁选项与按钮提供悬停反馈，清洁过程使用连续高光动画
- 窗口固定为 760 × 560，禁用缩放和全屏
- 加固输入恢复机制，覆盖启动失败、手动退出、5 分钟超时、应用退出、睡眠和会话切换
- 修复 Finder、Spotlight 与 Dock 中图标边缘高光和白色阴影异常
- Redesigned the home screen, guidance dialogs, and active-cleaning views
- Added hover feedback and continuous cleaning motion
- Fixed the window at 760 × 560 with resizing and full screen disabled
- Hardened input restoration for startup failures, manual exit, timeout, app termination, sleep, and session changes
- Fixed irregular edge highlights and white shadows around the icon in Finder, Spotlight, and the Dock

`v0.2.0` 和 `v0.2.1` 与本版本功能范围相同，后续变化仅为图标修正，因此不再单独保留。

Versions `v0.2.0` and `v0.2.1` had the same functional scope and only differed in intermediate icon corrections, so they are no longer retained separately.

## 安装 / Installation

1. 下载 `Mac-Clean-Helper-v0.2.2-macOS-arm64.zip`
2. 使用 `SHA256SUMS.txt` 核对下载文件
3. 解压后将“Mac 清洁助手”拖入“应用程序”文件夹
4. 打开应用，并按引导授予辅助功能权限

Download `Mac-Clean-Helper-v0.2.2-macOS-arm64.zip`, verify it with `SHA256SUMS.txt`, extract it, and move Mac Clean Helper to Applications. Grant Accessibility permission when prompted.

## 系统要求 / Requirements

- Apple Silicon Mac
- macOS 13 或更高版本 / macOS 13 or later
- 键盘和触控板清洁需要辅助功能权限 / Accessibility permission is required for keyboard and trackpad cleaning

当前不支持 Intel Mac、Mac App Store 安装和自动更新。

Intel Macs, Mac App Store installation, and automatic updates are not currently supported.

## 完整性校验 / Integrity

`Mac-Clean-Helper-v0.2.2-macOS-arm64.zip`

SHA-256: `b615f515aa9e204a26d3b68a3b1e029ef07243b16044ee9723711652cd51760a`

安装包已完成 Developer ID 签名和 Apple 公证，并通过 Gatekeeper 验证。应用不记录、不保存或上传输入内容，当前版本不联网，也不包含广告或统计 SDK。

The package is signed with Developer ID, notarized by Apple, and accepted by Gatekeeper. The app does not record, store, or upload input contents. This version makes no network connections and contains no advertising or analytics SDKs.
