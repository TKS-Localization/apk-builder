[English](./README.md)

# 闪耀星骑士 自动打包项目

[![Build Status](https://github.com/TKS-Localization/apk-builder/actions/workflows/build-apk.yml/badge.svg)](https://github.com/TKS-Localization/apk-builder/actions)

这是一个用于自动构建《闪耀星骑士》(Twinkle Star Knights) 修改版 APK 的项目。

本项目利用 GitHub Actions 自动检测游戏的最新版本，下载官方 APK，注入 mod 功能，然后重新打包并发布到 [Releases 页面](https://github.com/TKS-Localization/apk-builder/releases)。

## ✨ 功能

*   **自动更新**：每日定时检查并构建最新版本的游戏。
*   **Mod 注入**：为加载自定义资源（如汉化补丁）提供了基础支持。

## 🚀 如何使用

### 1. 下载并安装 APK

请前往本项目的 **[Releases 页面](https://github.com/TKS-Localization/apk-builder/releases)** 下载最新版本的 `.apk` 文件并安装。

### 2. 加载中文汉化补丁 (可选)

本仓库只提供带 mod 功能的 APK 基础包，**不包含任何翻译文件**。如需加载中文汉化，请按照以下步骤操作：

1.  **安装本仓库发布的 APK**。

2.  **下载汉化文件**。
    *   请前往汉化项目仓库：**[点击这里访问汉化仓库](https://github.com/TKS-Localization/translation-data)**
    *   下载最新的汉化资源包（通常是一个 `.zip` 文件）。

3.  **将汉化文件放置到正确位置**。
    *   解压你下载的 `.zip` 文件。
    *   使用你的手机文件管理器，在以下路径创建 `TskModder` 文件夹（如果不存在的话）：
      ```
      Android/data/jp.co.fanzagames.twinklestarknightsx_a/files/TskModder
      ```
    *   将解压后得到的**所有文件和文件夹**（例如字体文件和翻译文本文件）复制到 `TskModder` 文件夹内。

    > **重要提示:**
    > 在较新版本的 Android 系统上，`Android/data` 目录可能无法通过系统自带的文件管理器访问。你可能需要使用第三方文件管理器应用（如 X-plore, Solid Explorer, MT管理器等）来访问此路径。

4.  **启动游戏**。
    *   完成以上步骤后，重新启动游戏即可看到汉化效果。

## ⚠️ 免责声明

*   本软件仅供学习和技术交流使用，请勿用于商业用途。
*   使用本软件所造成的一切后果，由用户自行承担。
*   本项目与《闪耀星骑士》的开发商或发行商没有任何关联。