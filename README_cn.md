# Anki mimi

- [English](./README.md)

## 🚀 概述
一款基于 [Anki‑Sidebar](https://github.com/tszones/Anki‑Sidebar) 的 VS Code 扩展，用于 Anki 卡片复习。  
支持深色模式、色彩反转和键盘快捷键，实现无缝的 Anki 集成。

## ✅ 功能
- 🖼️ 深色模式兼容的图片色彩反转
- ⏱️ 带状态栏的计时器和进度跟踪
- 📝 Anki 卡片的 Markdown 导出
- 🔄 卡片导航的键盘快捷键
- 📚 卡包管理与复习追踪

## 📦 安装
1. [安装 VS Code](https://code.visualstudio.com/)
2. [从 VS Marketplace 安装扩展](https://marketplace.visualstudio.com/items?itemName=frunoob.ankimini)
3. 在 `settings.json` 中配置 AnkiConnect API 和其他选项：

   ```json
   {
     // AnkiConnect 监听地址
     "ankiview.api": "http://localhost:8765",

     // 侧边视图使用的字体大小 (px)
     "ankiview.fontSize": 11,

     // 显示/隐藏答案按钮
     "ankiview.showButton": false,

     // 警告时间倍数 (需重新加载)
     "ankiview.TimeBar.warnThreshold": 0.66
   }
   ```

## ⌨️ 快捷键
| 操作 | 默认键 (Windows/Linux) | macOS |
|------|-----------------------------|-------|
| 显示答案 | Ctrl+Alt+` | `Space` |
| 撤销 | `Ctrl+Alt+Z` | `⌘+Z` |
| 容易程度 1 | `Ctrl+Alt+1` | `⌘+1` |
| 容易程度 2 | `Ctrl+Alt+2` | `⌘+2` |
| 容易程度 3 | `Ctrl+Alt+3` | `⌘+3` |
| 容易程度 4 | `Ctrl+Alt+4` | `⌘+4` |

> **提示** – 若偏好自定义快捷键，可编辑 VS Code 中的 `keybindings.json` 文件。

## 🧪 使用方法
- 按 `Space` (macOS) 或 "ctrl+alt+`" (Win/Linux) 显示答案。
- 使用 `⌘+1/2/3/4` (macOS) 或 `Ctrl+Alt+1/2/3/4` (Win/Linux) 标记所选容易程度。
- 状态栏查看统计数据。

## 🛠️ 参与贡献
1. 叉该项目仓库  
2. 创建 feature/bugfix 分支  
3. 本地测试更改  
4. 提交 Pull Request

## 📄 许可证
[Apache 2.0](LICENSE)