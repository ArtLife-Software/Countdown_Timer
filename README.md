# Countdown Timer

![OS](https://img.shields.io/badge/OS-Windows-blue?style=flat-square&logo=windows)
![Language](https://img.shields.io/badge/Language-VB.NET_2012-854CC9?style=flat-square&logo=visual-studio)
![License](https://img.shields.io/badge/License-GPL_v3-red?style=flat-square)
![Latest Downloads](https://img.shields.io/github/downloads/ArtLife-Software/Countdown_Timer/latest/total?style=flat-square&logo=github)
![Latest Release](https://img.shields.io/github/v/release/ArtLife-Software/Countdown_Timer?style=flat-square&color=blue)

![正體中文](https://img.shields.io/badge/Locale-%F0%9F%87%B9%F0%9F%87%B3%20%E6%AD%A3%E9%AB%94%E4%B8%AD%E6%96%87-orange?style=flat-square)
![English](https://img.shields.io/badge/Locale-%F0%9F%87%BA%F0%9F%87%B8%20English-blue?style=flat-square)
![日本語](https://img.shields.io/badge/Locale-%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC%E8%AA%9E-red?style=flat-square)
![한국어](https://img.shields.io/badge/Locale-%F0%9F%87%B0%F0%9F%87%B7%20%ED%95%9C%EA%B5%AD%EC%96%B4-green?style=flat-square)

Windows 桌面倒數計時器，支援多視窗同時運作、彈性提醒、語音倒數與通知視窗。常駐系統匣，開箱即用。

---

## 功能說明

### 計時器視窗

每個計時器為獨立視窗，可自由縮放與拖移。視窗顯示：

- 倒數時間（時：分：秒，可開啟小數）
- 進度條與百分比
- 已經過時間（正數計時）
- 預計結束時間
- 操作按鈕（開始 / 暫停 / 停止 / 重啟 / 繼續 / 初始化）

支援**負計時模式**，歸零後繼續往負數倒數。

### 多視窗管理

- 可同時開啟多個計時器，每個獨立運作
- 相同設定檔可開啟多個實例，標題列自動加上 `#N` 編號
- **自動排列**：一鍵將所有視窗整齊排列於螢幕工作區

### 系統匣

程式常駐系統匣，右鍵選單提供：

- 啟動視窗（LaunchForm）
- 新增倒數計時器
- 預設計時器設定
- 自動排列計時器
- 關閉所有計時器
- 語系切換
- 關於
- 結束程式

雙擊系統匣圖示可快速開啟啟動視窗。

### 設定

每個計時器有獨立設定，分為以下頁籤：

**基本**
- 時長（時 / 分 / 秒）
- 負計時、小數顯示（1–3 位）、正數計時、結束時間顯示
- 計時器名稱（單一設定模式）

**外觀**
- 字型、前景色、背景色、進度條顏色
- 視窗縮放比例（50% / 75% / 100% / 150% / 200% 或自訂 25%–400%）
- 最上層顯示

**間隔提醒（AI）**
每隔固定時間觸發一次，支援秒 / 分 / 時單位。

**剩餘提醒（AR）**
剩餘時間低於門檻時觸發，持續提醒至歸零。可設定提醒時顯示的小數位數。

**結束提醒（AE）**
計時結束時觸發，持續提醒。可設定提醒時顯示的小數位數。

各提醒皆可設定：
- 音效：預設音效 / 自訂 WAV / 無聲
- 顏色切換：前景色 / 背景色 / 進度條色可各自啟用
- 通知視窗：可啟用並自訂通知文字

**語音倒數（VO）**
最後 3 / 5 / 10 秒播放語音倒數檔（`Sound_effects\Countdown_voice_XX.wav`）。

### 通知視窗

各提醒觸發時，可在螢幕上方彈出無邊框通知視窗，顯示：

- 計時器名稱
- 目前計時時間（AR / AE 會持續更新）
- 自訂通知文字

多個通知視窗會自動排列，從螢幕頂部置中往兩側展開，避免重疊。

### 啟動視窗（LaunchForm）

集中管理所有計時器設定檔，設定檔清單顯示名稱、隨程式啟動狀態、時長與最後修改時間，支援欄位排序。

操作分為以下頁籤：

**啟動**

| 功能 | 說明 |
|------|------|
| 啟動 | 開啟選取的計時器視窗 |
| 啟動並開始計時 | 開啟並立即開始 |
| 啟動數量 | 同一設定檔同時開啟多個實例 |

**再製**

| 功能 | 說明 |
|------|------|
| 新增 | 建立新計時器設定檔（可自訂名稱） |
| 再製 | 複製選取的設定檔，支援一次多份（可自訂各份名稱） |
| 再製數量 | 指定每個設定檔複製的份數 |

**設定**

| 功能 | 說明 |
|------|------|
| 設定 | 開啟單一設定視窗 |
| 批次設定 | 同時修改多個計時器的設定（僅套用有變更的欄位） |
| 更名 | 批次重新命名設定檔 |

**起止**

| 功能 | 說明 |
|------|------|
| 隨程式啟動（切換） | 設定計時器是否隨程式啟動時自動開啟 |
| 關閉 | 關閉選取的計時器視窗 |
| 刪除 | 刪除選取的設定檔（計時中不可刪除） |

**批次控制**

對選取的計時器（未選取則對全部已開啟的計時器）執行：開始、重啟、暫停、繼續、停止、初始化。

清單下方另有選取工具列：全選、全不選、反選、重新整理，以及**啟動程式時行為**設定。

### 啟動程式時行為

可設定程式啟動時自動執行下列任一項或組合：

- 開啟已標記「隨程式啟動」的計時器
- 重新開啟上次關閉的計時器
- 開啟新計時器

---

## 目錄結構

```
Countdown Timer.exe
Config\                  # 計時器設定檔（.ini）與啟動設定
Location\                # 視窗位置記錄（.ini）
Sound_effects\           # 自訂音效與語音倒數檔案
Language\                # 多語系語言檔（.ini）
Countdown_Timer.ico      # 自訂圖示（可選）
```

## 多語系支援

內建正體中文、英文、日文、韓文，優先使用設定值，若未設定，則根據系統語系自動偵測預設語言。可在系統匣選單的語系子選單中切換，重新啟動後生效。

語言檔位於 `Language\` 目錄，支援自訂語言檔擴充。

## 音效檔案

將 WAV 檔案放入 `Sound_effects\` 目錄：

| 檔名 | 用途 |
|------|------|
| `Interval.wav` | 間隔提醒預設音效 |
| `Remainder.wav` | 剩餘提醒預設音效 |
| `End.wav` | 結束提醒預設音效 |
| `Countdown_voice_03.wav` | 語音倒數 3 秒版 |
| `Countdown_voice_05.wav` | 語音倒數 5 秒版 |
| `Countdown_voice_10.wav` | 語音倒數 10 秒版 |

未放置檔案時，自動退回使用 Windows 內建通知音效。

## 自訂圖示

將 `Countdown_Timer.ico` 放於程式同目錄下即可套用至視窗與系統匣。

---

## 系統需求

- Windows 10 x64 以上
- .NET Framework 4.x

---

## 安裝與執行

可安裝，或解壓縮後直接執行 `Countdown_Timer.exe`。

首次啟動會自動建立預設設定檔。

---

## 錯誤記錄

程式發生未處理例外時，會自動寫入同目錄的 `crash.log`，格式為：

```
[yyyy-MM-dd HH:mm:ss.fff] ThreadException
...
---
```

---

## 授權

[GPL-3.0 License](LICENSE)

---

## 作者

林彥丞  
[GitHub](https://github.com/ArtLife-Software) ·
[Facebook 社群](https://www.facebook.com/groups/vba.club) ·
lin.yancheng@outlook.com
