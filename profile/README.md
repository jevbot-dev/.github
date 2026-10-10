## Jevbot

**把你想完成的事，告诉电脑上的应用。**

Jevbot 是一个跑在桌面上的 AI 助手：围绕一个应用创建任务，或者让多个应用协作完成一件事。你描述目标、选好要用的应用，Jevbot 调用这些应用的能力去执行；每一步都看得见，需要批准的操作由你确认，随时可以停下或补充要求。

聊天场景里，它会读懂对方这句话想要什么，给出分析和候选回复，点一下填入输入框——**发送永远由你自己按**。

### 下载

| 平台 | 要求 | 仓库 |
|---|---|---|
| **macOS** | Apple Silicon · macOS 14+ | [⬇ 下载](https://github.com/jevbot-dev/jevbot-mac/releases/latest) · [jevbot-mac](https://github.com/jevbot-dev/jevbot-mac) · [更新日志](https://github.com/jevbot-dev/jevbot-mac/blob/release/CHANGELOG.md) |
| **Windows** | Windows 11 / Windows 10 2004+ · x64 / ARM64 | [jevbot-windows](https://github.com/jevbot-dev/jevbot-windows)（安装包即将发布） |

### 应用桥接（MCP）

有些应用没有脚本接口，我们为它们写了 MCP 桥接器。Jevbot 在应用商店里一键接入，也可以单独给任何 MCP 客户端使用。每个版本都由 GitHub Actions 从标签构建，附带构建证明，可复现校验。

| 仓库 | 连接的应用 | 能做什么 |
|---|---|---|
| [developer-mcp](https://github.com/jevbot-dev/developer-mcp) | Apple [Developer](https://apps.apple.com/app/apple-developer/id640199958) | 搜索 2014–2026 年 WWDC 讲座字幕，在 Developer 里打开到某一秒并播放 |
| [obsidian-mcp](https://github.com/jevbot-dev/obsidian-mcp) | [Obsidian](https://obsidian.md) | 通过官方 CLI 和 URI 列出、搜索、读取、新建和追加笔记，不装插件、不碰私有数据库 |

### 相关项目

同一个团队在 [orca-studio](https://github.com/orca-studio) 做的开源应用，可以和 Jevbot 一起用：

- [**Orca PPT**](https://github.com/orca-studio/orca-ppt) — agent-native 演示稿工作台，自带 MCP 和 PPT Skill，让你的 AI 助手做出带电影级转场的演示稿。[官网 ↗](https://ppt.orca-studio.ai)
- [**Compositor**](https://github.com/orca-studio/Compositor) — Mac 上的 Photoshop 替代品。Jevbot 的[人像修图演示](https://x.com/jevbot_dev/status/2108150994353946732)就是和它一起完成的。

### 联系

[提 Issue](https://github.com/jevbot-dev/jevbot-mac/issues) · X [@jevbot_dev](https://x.com/jevbot_dev) · X [@zhenwusw](https://x.com/zhenwusw) · [微信与社群](https://github.com/jevbot-dev/jevbot-mac#connect) · [jevbot.dev](https://jevbot.dev/)
