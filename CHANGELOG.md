# 更新记录 / Changelog

## [0.2.0] - 2026-09-12

正式发布版本 0.2.0，构建号 4。

Production release 0.2.0, build 4.

### 界面与交互 / Interface and interaction

- 全面调整首页、清洁说明弹窗和清洁过程界面
- 首页选项与按钮加入统一的悬停反馈
- 清洁过程使用无停顿循环的高光动画
- 优化说明文案、倒计时提示与重点操作高亮
- 更新应用图标，并优化 Dock 中的显示效果
- 窗口固定为 760 × 560，禁用缩放与全屏
- Redesigned the home screen, cleaning guidance dialogs, and active-cleaning views
- Added consistent hover feedback to home options and buttons
- Added continuous highlight motion during cleaning
- Refined guidance copy, countdown emphasis, and action highlighting
- Updated the app icon and its Dock presentation
- Fixed the window at 760 × 560 with resizing and full screen disabled

### 安全与恢复 / Safety and recovery

- 输入拦截启动失败时立即回滚已启用的资源
- 防止延迟启动的旧监听器在会话取消后重新激活
- 防止旧会话清理过程影响新会话
- 在手动退出、5 分钟超时、应用退出、睡眠与会话切换时恢复输入
- Roll back all activated resources immediately when input blocking fails to start
- Prevent cancelled late listeners from becoming active
- Prevent cleanup from an earlier session from affecting a newer session
- Restore input on manual exit, the five-minute timeout, app termination, sleep, and session changes

### 发布状态 / Release status

安装包已完成 Developer ID 签名和 Apple 公证，并通过 Gatekeeper 验证。

The package is signed with Developer ID, notarized by Apple, and accepted by Gatekeeper.

## [0.1.0] - 2026-09-05

首个 GitHub 公开测试版。

First public GitHub beta.

### 新增 / Added

- 键盘清洁、触控板清洁和屏幕清洁三种模式。
- 键盘模式可使用鼠标或触控板点击“结束清洁”安全退出。
- 触控板模式可通过 ESC 或 Q 安全退出。
- 屏幕模式只覆盖 MacBook 内置显示屏，可通过点按鼠标或按任意键安全退出。
- 键盘、触控板和屏幕清洁动画采用统一的横向扫描效果。
- 每次清洁禁用最长只会维持 5 分钟，以防由于特殊或意外情况导致无法退出禁用。
- 在退出、超时、睡眠或会话切换时恢复输入。
- 本机处理输入事件，不记录、不保存、不上传输入内容。
- Keyboard, trackpad, and screen cleaning modes.
- Safe exit from keyboard cleaning by clicking “End Cleaning” with the mouse or trackpad.
- Safe exit from trackpad cleaning with Escape or Q.
- Screen cleaning covers only the built-in MacBook display and exits safely with a mouse click or any key press.
- Unified horizontal scan animations for keyboard, trackpad, and screen cleaning.
- Input blocking lasts no longer than five minutes per cleaning session, preventing an unexpected condition from leaving input disabled indefinitely.
- Input restoration on exit, timeout, sleep, or session change.
- Local-only input processing with no recording, storage, or upload of input contents.

### 本次构建更新 / Updated build

- 修复外接显示器上屏幕清洁状态窗口变黑的问题。
- 屏幕清洁时统一隐藏鼠标指针，并明确键盘和点按退出方式。
- 清洁过程的最后 60 秒显示逐秒倒计时。
- 统一键盘、触控板和屏幕清洁动画。
- 为应用内所有按钮增加统一且更明显的悬停反馈。
- Fixed the screen-cleaning status window turning black on an external display.
- The pointer is consistently hidden during screen cleaning, with clear keyboard and click exit guidance.
- Added a per-second countdown during the final 60 seconds of a cleaning session.
- Unified keyboard, trackpad, and screen cleaning animations.
- Added consistent, more visible hover feedback to every in-app button.

### 系统要求 / Requirements

- Apple Silicon Mac
- macOS 13 或更高版本 / macOS 13 or later

### 发布状态 / Release status

安装包已完成 Developer ID 签名和 Apple 公证，并已通过 GitHub 真实下载验收。

The package is signed with Developer ID, notarized by Apple, and verified through a real GitHub download acceptance test.
