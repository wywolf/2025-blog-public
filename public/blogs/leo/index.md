使用 macOS “自动操作 (Automator)” 创建全局快捷键
如果你想通过 Command + Shift + W 在任何地方直接打开 Chrome 或特定网址，可以利用 macOS 系统功能：
1. 打开 自动操作 (Automator) 应用程序，选择“快速操作 (Quick Action)”。
2. 设置“工作流程收到”为 “无输入”。
3. 在左侧搜索“运行 AppleScript”，拖入右侧，输入：
···
tell application "Google Chrome" to activate
···
4. 保存（例如命名为 "OpenChrome"）。
5. 前往 系统设置 -> 键盘 -> 键盘快捷键 -> 服务 -> 通用。
6. 找到 "OpenChrome"，为其设置你想要的快捷键。 