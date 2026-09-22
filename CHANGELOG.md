# 更新记录 / Changelog

## [0.2.3] - 2026-09-22

修复 macOS 27 上窗口左上角关闭与最小化按钮异常放大的问题。清洁模式和输入恢复逻辑未变。

Fix oversized close and minimize window buttons on macOS 27. Cleaning modes and input-restoration behavior are unchanged.

## [0.2.2] - 2026-09-12

`0.2.0`、`0.2.1` 与本版本功能范围相同，后续变化仅用于逐步修正发布图标，现统一合并为 `0.2.2`。

Versions `0.2.0` and `0.2.1` had the same functional scope. Subsequent changes only refined the release icon and are consolidated into `0.2.2`.

### 界面与交互 / Interface and interaction

- 重新设计首页、权限提示、清洁说明和清洁过程页面
- 为清洁选项和按钮加入统一悬停反馈
- 清洁过程使用无停顿循环的高光动画
- 优化说明文案、重点操作高亮和最后一分钟倒计时
- 窗口固定为 760 × 560，禁用缩放和全屏
- Redesigned the home screen, permission guidance, cleaning instructions, and active-cleaning views
- Added consistent hover feedback and continuous cleaning motion
- Refined guidance, action emphasis, and the final-minute countdown
- Fixed the window at 760 × 560 with resizing and full screen disabled

### 输入安全与恢复 / Input safety and recovery

- 输入拦截启动失败时立即回滚已启用的资源
- 防止已取消或超时的旧监听器重新激活
- 防止旧会话清理影响新的清洁会话
- 在手动退出、5 分钟超时、应用退出、睡眠和会话切换时恢复输入
- Roll back activated resources when input interception fails to start
- Prevent cancelled or timed-out listeners from activating later
- Prevent cleanup from an earlier session from affecting a newer session
- Restore input on manual exit, timeout, app termination, sleep, and session changes

### 应用图标 / App icon

- 使用原生 Icon Composer `.icon` 资源参与 Xcode 编译，避免系统重复处理预渲染边缘
- 关闭额外的高光、模糊和阴影效果
- 在 Finder、Spotlight 和 Dock 中完成可见验收
- Compile the native Icon Composer `.icon` source directly to avoid double-processing a pre-rendered edge
- Disable additional specular, blur, and shadow effects
- Complete visual acceptance in Finder, Spotlight, and the Dock

## [0.1.0] - 2026-09-05

首个公开版本。

First public release.

- 键盘、触控板和屏幕三种清洁模式
- 每次清洁最长 5 分钟
- 在退出、超时、睡眠或会话切换时恢复输入
- 本机处理输入事件，不记录、不保存、不上传输入内容
- Keyboard, trackpad, and screen cleaning modes
- A five-minute maximum cleaning session
- Input restoration on exit, timeout, sleep, or session change
- Local-only input processing with no recording, storage, or upload of input contents
