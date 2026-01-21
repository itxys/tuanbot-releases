# Tuanbot Releases / 发行版

<p align="center">
  <img src="./loading.png" alt="Tuanbot Logo" width="720" />
</p>

<p align="center">
  <b>Desktop Pet + AI Assistant</b><br/>
  <sub>Windows installer available now · Multi-platform coming soon</sub>
</p>

<p align="center">
  <a href="#-中文">中文</a> · <a href="#-english">English</a> ·
  <a href="https://github.com/itxys/tuanbot">Source</a> ·
  <a href="https://github.com/itxys/tuanbot/issues">Issues</a>
</p>

---

## ⬇️ Windows Download (Latest)

<p align="center">
  <a href="https://github.com/itxys/tuanbot-releases/releases/latest/download/tuanbot_win_latest.exe">
    <img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows%20x64-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  </a>
</p>

---

## 📌 中文

### 这是什么仓库？
这是 **Tuanbot 的发行版仓库**，用于存放安装包与自动更新所需文件（例如 `latest.yml`、`.blockmap`）。

- 源码仓库：`https://github.com/itxys/tuanbot`
- 反馈问题：`https://github.com/itxys/tuanbot/issues`

### ✅ 下载安装
当前提供 Windows 安装包：

- Windows（稳定直链）：`tuanbot_win_latest.exe`

点击页面上方按钮即可下载最新版本。

### 🧩 文件说明（自动更新相关）
本仓库可能包含以下文件：

| 文件 | 用途 |
|---|---|
| `tuanbot_win_<version>.exe` | 带版本号的 Windows 安装包（可用于回滚） |
| `tuanbot_win_latest.exe` | 永久固定的最新 Windows 安装包直链 |
| `latest.yml` | electron-updater 用于检测最新版本 |
| `*.blockmap` | 增量更新/差分更新映射文件 |

> 普通安装只需要下载 `.exe` 安装包；`latest.yml` 与 `.blockmap` 主要服务于应用内自动更新。

### 🗺️ 平台支持
- Windows：已支持
- macOS / Linux：后续会在 Releases 中提供

---

## 🌍 English

### What is this repository?
This is the **release-only repository** for Tuanbot. It hosts installers and auto-update metadata (e.g. `latest.yml`, `.blockmap`).

- Source: `https://github.com/itxys/tuanbot`
- Issues: `https://github.com/itxys/tuanbot/issues`

### ✅ Download & Install
Windows installer is available:

- Windows (stable direct link): `tuanbot_win_latest.exe`

Use the download button above to get the latest build.

### 🧩 Files in this repo (Auto-update)
| File | Purpose |
|---|---|
| `tuanbot_win_<version>.exe` | Versioned Windows installer (useful for rollback) |
| `tuanbot_win_latest.exe` | Stable direct link to the latest Windows installer |
| `latest.yml` | Update manifest used by electron-updater |
| `*.blockmap` | Differential update mapping files |

> For manual install, you only need the `.exe` installer. `latest.yml` and `.blockmap` are primarily for in-app auto updates.

### 🗺️ Platform Support
- Windows: supported now
- macOS / Linux: coming soon (will appear in Releases)
