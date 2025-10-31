[简体中文](./README.zh-CN.md)

# Twinkle Star Knights Auto-Packaging Project

[![Build Status](https://github.com/TKS-Localization/apk-builder/actions/workflows/build-apk.yml/badge.svg)](https://github.com/TKS-Localization/apk-builder/actions)

This project automatically builds a modified APK for the game "Twinkle Star Knights".

It uses GitHub Actions to monitor for new game versions, download the official APK, inject modding capabilities, and then repackage and publish it to the [Releases page](https://github.com/TKS-Localization/apk-builder/releases).

## ✨ Features

*   **Auto-Update**: Automatically checks for and builds the latest game version daily.
*   **Mod Injection**: Provides the necessary foundation for loading custom assets, such as translation patches.

## 🚀 How to Use

### 1. Download and Install the APK

Please go to the **[Releases Page](https://github.com/TKS-Localization/apk-builder/releases)** of this project to download and install the latest `.apk` file.

### 2. Optional: How to Enable Chinese Translation

This repository only provides the base APK with modding capabilities and **does not include any translation files**. To enable the Chinese translation, please follow these steps:

1.  **Install the APK** provided by this repository.

2.  **Download the translation files**.
    *   Go to the translation project repository: **[Click here to visit the translation repository](https://github.com/TKS-Localization/translation-data)**
    *   Download the latest translation assets pack (usually a `.zip` file).

3.  **Place the translation files in the correct directory**.
    *   Unzip the `.zip` file you downloaded.
    *   Using a file manager on your phone, create a folder named `TskModder` inside the following path (if it doesn't already exist):
      ```
      Android/data/jp.co.fanzagames.twinklestarknightsx_a/files/TskModder
      ```
    *   Copy **all the extracted files and folders** (e.g., font files and translation text files) into the `TskModder` folder.

    > **Important Note:**
    > On newer versions of Android, the `Android/data` directory may be restricted. You might need to use a third-party file manager app (like X-plore, Solid Explorer, etc.) to access this path.

4.  **Launch the game**.
    *   After completing the steps above, restart the game to see the translation.

## ⚠️ Disclaimer

*   This software is intended for educational and technical communication purposes only. Do not use it for commercial purposes.
*   The user is solely responsible for any consequences arising from the use of this software.
*   This project is not affiliated with the developers or publishers of "Twinkle Star Knights".