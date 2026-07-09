# Code Geass - Black Requiem 繁體中文漢化模組
**(Traditional Chinese Translation Mod)**

本專案為《鋼鐵雄心4 (Hearts of Iron IV)》大型模組 **[Code Geass - Black Requiem](https://steamcommunity.com/workshop/filedetails/?id=2785523030)** 的繁體中文在地化翻譯專案。

This repository contains the Traditional Chinese translation files for the Hearts of Iron IV mod **Code Geass - Black Requiem**.

---

## 🇹🇼 中文說明 (Traditional Chinese)

### 📌 關於本專案
將《反叛的魯路修》世界觀帶入 HOI4 的精彩模組「Black Requiem」文本量龐大。為了讓中文玩家能無障礙地體驗機甲戰鬥與豐富的政治劇情，本專案致力於將所有英文文本翻譯為繁體中文。

### ⚙️ 自動化工作流 (Automated Workflow)
本專案採用全自動化的翻譯同步架構：
1. **翻譯協作平台**：所有翻譯工作皆在 [ParaTranz] 平台上進行。
2. **GitHub Actions 每日同步**：透過自動化腳本，GitHub 機器人會自動抓取 ParaTranz 上最新打包的翻譯檔。
3. **格式自動轉換**：腳本會自動將 P 社的 `.yml` 檔案轉換為遊戲引擎規定的 `UTF-8 WITH BOM` 編碼以確保遊戲正確讀取。
4. **自動推送**：轉換完成的檔案將自動 Commit 至本倉庫的 `localisation/english` 目錄下。

### 🚀 如何使用
1. 請於 Steam 工作坊訂閱發布的[漢化版本](https://steamcommunity.com/sharedfiles/filedetails/?id=3760459263)。

### 🤝 參與翻譯
如果你對《Code Geass》充滿熱情，歡迎加入我們的翻譯行列！請前往本專案的 ParaTranz 頁面[申請加入](https://paratranz.cn/projects/19644)。

---

## 🇬🇧 English Description

### 📌 About
This project provides a complete Traditional Chinese localization for the HOI4 mod **Code Geass - Black Requiem**, allowing Chinese-speaking players to fully enjoy the rich lore, Knightmare combat, and political events of the Code Geass universe.

### ⚙️ Automated CI/CD Workflow
This repository features a fully automated translation pipeline:
* **Translation Platform**: All translations are crowdsourced and managed via [ParaTranz].
* **GitHub Actions Sync**: A custom workflow automatically fetches the latest translation artifacts from ParaTranz via API.
* **Format Conversion**: The workflow automatically parses the downloaded `.yml` files, converts the encoding to `UTF-8 WITH BOM` (required by the Clausewitz Engine).
* **Auto-Commit**: The processed files are automatically pushed to the `localisation/english` directory in this repository.

### 🚀 How to Use
1. Subscribe to the localized mod on the [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3760459263).

### ⚖️ Credits & Disclaimer
* All original assets, mechanics, and lore belong to the **Code Geass - Black Requiem Development Team**. 
* This is a fan-made, non-profit translation project.
