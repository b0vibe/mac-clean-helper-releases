# 隐私说明 / Privacy Notice

生效日期 / Effective date: 2026-08-30

## 中文

Mac 清洁助手是一款在本机运行的 macOS 工具，用于在清洁 Mac 时临时拦截键盘或触控板输入，或显示屏幕清洁覆盖层。

### 我们不收集什么

- 不记录、不保存、不上传按键或点击内容。
- 不收集个人信息、设备标识符或使用统计信息。
- 不包含广告、分析或崩溃上报 SDK。
- 不创建账户，也不要求登录。
- 当前版本不进行网络通信。

### 输入事件如何处理

键盘和触控板模式需要 macOS“辅助功能”权限。输入事件只在设备内存中即时处理，用于临时阻止输入，以及识别 ESC 或 Q 等安全退出操作。应用退出相应模式后，不保留这些事件。

屏幕清洁模式只在本机显示覆盖层，不读取或上传屏幕内容。

### 权限控制

你可以随时前往“系统设置 → 隐私与安全性 → 辅助功能”关闭 Mac 清洁助手的权限。关闭后，需要输入拦截的模式将无法正常工作。

### 变更与联系

如果未来版本加入联网、统计或其他数据处理功能，我们会在启用前更新本说明。问题可在 [GitHub Issues](https://github.com/b0vibe/mac-clean-helper-releases/issues) 提交。

## English

Mac Clean Helper is a local macOS utility that temporarily blocks keyboard or trackpad input while you clean your Mac, or displays an overlay for screen cleaning.

### What we do not collect

- We do not record, store, or upload keystrokes or click contents.
- We do not collect personal information, device identifiers, or usage analytics.
- The app contains no advertising, analytics, or crash-reporting SDKs.
- No account or sign-in is required.
- The current version makes no network connections.

### How input events are handled

Keyboard and trackpad modes require macOS Accessibility permission. Input events are processed immediately and only in device memory to temporarily block input and recognize safe exit actions such as Escape or Q. The events are not retained after the mode ends.

Screen cleaning mode only displays a local overlay. It does not read or upload screen contents.

### Permission control

You can revoke access at any time in System Settings → Privacy & Security → Accessibility. Modes that block input will not work correctly without this permission.

### Changes and contact

If a future version adds networking, analytics, or other data processing, this notice will be updated before those features are enabled. Questions can be submitted through [GitHub Issues](https://github.com/b0vibe/mac-clean-helper-releases/issues).
