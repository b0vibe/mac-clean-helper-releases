# 更新记录 / Changelog

## [0.1.0] - 2026-09-04

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

### 系统要求 / Requirements

- Apple Silicon Mac
- macOS 13 或更高版本 / macOS 13 or later

### 发布状态 / Release status

安装包已完成 Developer ID 签名和 Apple 公证，并已通过 GitHub 真实下载验收。

The package is signed with Developer ID, notarized by Apple, and verified through a real GitHub download acceptance test.
