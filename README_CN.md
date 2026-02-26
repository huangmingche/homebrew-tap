# Homebrew Tap

[English](./README.md) | **中文**

[![homebrew-tap](https://img.shields.io/badge/brew_tap-huangmingche%2Ftap-orange?style=flat-square&logo=homebrew&logoColor=white)](https://github.com/huangmingche/homebrew-tap)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

[huangmingche](https://github.com/huangmingche) 项目的 Homebrew 安装源。

## 安装

```bash
brew tap huangmingche/tap
brew install <formula>
```

## 可用工具

| 工具 | 版本 | 说明 |
|------|------|------|
| [browsercli](https://github.com/huangmingche/browsercli) | 1.0.4 | 本地优先的浏览器渲染命令行工具，面向 AI 智能体和开发者 |
| [camgrab](https://github.com/huangmingche/camgrab) | 1.0.0 | 高速单二进制 IP 摄像头命令行工具，支持抓拍、录制与运动检测 |

### browsercli

```bash
brew install huangmingche/tap/browsercli
```

本地优先的浏览器渲染命令行工具，面向 AI 智能体和开发者。在本地目录编写 HTML/CSS/JS，在真实 Chromium 浏览器中渲染，完整支持 DevTools 控制。

### camgrab

```bash
brew install huangmingche/tap/camgrab
```

高速单二进制 IP 摄像头命令行工具，支持抓拍、录制与运动检测。零外部依赖，无需安装 ffmpeg。
