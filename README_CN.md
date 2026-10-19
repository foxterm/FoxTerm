[English](README.md) | [中文文档](README_CN.md)

# FoxTerm

> 快速、私密的终端工具 — 由工程师打造，为工程师而生。

SSH · VNC · SFTP · Docker · Podman — 高性能、隐私优先的终端套件，支持 macOS 和 iOS。原生 Swift + Metal，零遥测。

## 功能特性

- **SSH 终端** — ed25519、主机密钥校验、256 色、UTF-8、近零延迟
- **SFTP 文件管理** — 原生速度的安全传输
- **Metal 加速 VNC** — 流畅远程桌面，GPU 渲染
- **Docker & Podman** — 可视化容器管理
- **实时系统监控** — CPU、内存、温度、网络、磁盘、运行时间
- **原生性能** — 基于 Swift、Metal 及 C 原生库（OpenSSL、libssh、libvncclient）构建，非 Electron 套壳
- **零遥测** — 无追踪、无分析、无数据收集
- **硬件隔离凭据** — 私钥存储于 Apple 安全隔区与钥匙串
- **加密 iCloud 同步** — 配置通过你的私有 iCloud 容器加密同步

## 下载

| 平台 | 链接 |
|------|------|
| macOS (DMG) | [GitHub Releases](https://github.com/foxterm/FoxTerm/releases/latest/download/FoxTerm.dmg) |
| macOS & iOS/iPadOS | [App Store](https://apps.apple.com/us/app/foxterm/id6760452891) |
| 官网 | [foxterm.app](https://foxterm.app) |

## 核心库

| 仓库 | 说明 |
|------|------|
| [SSH](https://github.com/foxterm/SSH) | SSH 核心 — 会话、SFTP、SCP、Shell、端口转发、主机监控 |
| [VNC](https://github.com/foxterm/VNC) | VNC 客户端 — 远程桌面、帧渲染、键鼠输入、剪贴板 |
| [libetos](https://github.com/foxterm/libetos) | C 工具库 — Socket、缓冲区、加密、同步原语、Base64 |
| [Sync](https://github.com/foxterm/Sync) | 并发原语 — Atomic、Mutex、WaitGroup |
| [Proxy](https://github.com/foxterm/Proxy) | 网络代理 — SOCKS5、HTTP CONNECT |
| [Extension](https://github.com/foxterm/Extension) | Foundation 扩展 — String、Data、Integer、Color、IP、Net |
| [ChartUI](https://github.com/foxterm/ChartUI) | SwiftUI 图表 — 点阵分段条、负载环、饼图 |

## 系统要求

- macOS 14 (Sonoma) 或更高版本
- iOS / iPadOS

## FoxTerm Pro

免费版解锁全部功能 — SSH、SFTP、VNC、监控和容器管理 — 但有节点（服务器）数量上限。FoxTerm Pro 取消上限，支持**无限节点**，一个订阅同时解锁 macOS 和 iOS/iPadOS 客户端（同一 Apple ID）。

- **macOS（公证签名版）** — 使用 Pro 许可证密钥激活（月付、季付、年付或终身方案），购买后即时交付
- **iOS / iPadOS** — 购买后自动激活，无需许可证密钥

购买地址：[pay.foxterm.app](https://pay.foxterm.app)

## 自动更新

- 基于 Sparkle 的自动更新，签名 appcast
- Appcast 地址：<https://foxterm.app/appcast.xml>
- 更新入口：App 菜单 → **检查更新**

## 安全性

- **零遥测** — 连接日志永不离开你的本地环境
- **安全隔区** — Apple 钥匙串与安全隔区硬件隔离存储私钥
- **原生加密** — C 原生引擎，支持 Ed25519 和现代密码套件
- **iCloud 同步** — 配置仅通过你的私有加密 iCloud 容器同步

## 支持

- 邮箱：[foxterm@icloud.com](mailto:foxterm@icloud.com)
- 官网：[foxterm.app](https://foxterm.app)
