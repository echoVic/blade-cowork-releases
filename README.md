# Blade Cowork

智能协作终端 - AI Agent 驱动的代码协作工具

## 演示视频

https://github.com/user-attachments/assets/6d6d9b89-2360-439c-ba73-082267829b0a

## 功能特性

- AI Agent 驱动的代码协作
- MCP (Model Context Protocol) 支持
- 丰富的内置工具（文件操作、搜索、Shell 等）
- 多主题支持
- Skills 动态扩展系统

## 下载

从 [Releases](https://github.com/echoVic/blade-cowork-releases/releases) 页面下载对应架构的安装包：

### macOS
- **Apple Silicon (M1/M2/M3)**: `Blade Cowork-x.x.x-arm64.zip`
- **Intel Mac**: `Blade Cowork-x.x.x-x64.zip`

### 首次打开提示"已损坏"的解决方法

由于应用未经 Apple 签名，首次打开可能会提示：

> "Blade Cowork" 已损坏，无法打开。你应该将它移到废纸篓。

解决方法：打开终端，执行以下命令：

```bash
xattr -cr /Applications/Blade\ Cowork.app
```

如果应用不在 `/Applications` 目录，请替换为实际路径。

## 许可证

MIT License
