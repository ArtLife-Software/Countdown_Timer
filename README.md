# Countdown Timer

![OS](https://img.shields.io/badge/OS-Windows-blue?style=flat-square&logo=windows)
![Language](https://img.shields.io/badge/Language-VB.NET-854CC9?style=flat-square&logo=visual-studio)
![License](https://img.shields.io/badge/License-PolyForm--NC_1.0.0-red?style=flat-square)
![Latest Release](https://img.shields.io/github/v/release/ArtLife-Software/Countdown_Timer?style=flat-square&color=blue)
![Downloads](https://img.shields.io/github/downloads/ArtLife-Software/Countdown_Timer/total?style=flat-square&logo=github)

![正體中文](https://img.shields.io/badge/Locale-%F0%9F%87%B9%F0%9F%87%BC%20%E6%AD%A3%E9%AB%94%E4%B8%AD%E6%96%87-orange?style=flat-square)
![简体中文](https://img.shields.io/badge/Locale-%F0%9F%87%A8%F0%9F%87%B3%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-red?style=flat-square)
![日本語](https://img.shields.io/badge/Locale-%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC%E8%AA%9E-d62828?style=flat-square)
![한국어](https://img.shields.io/badge/Locale-%F0%9F%87%B0%F0%9F%87%B7%20%ED%95%9C%EA%B5%AD%EC%96%B4-green?style=flat-square)
![English](https://img.shields.io/badge/Locale-%F0%9F%87%BA%F0%9F%87%B8%20English-blue?style=flat-square)
![Español](https://img.shields.io/badge/Locale-%F0%9F%87%AA%F0%9F%87%B8%20Espa%C3%B1ol-yellow?style=flat-square)
![Français](https://img.shields.io/badge/Locale-%F0%9F%87%AB%F0%9F%87%B7%20Fran%C3%A7ais-0055A4?style=flat-square)
![Русский](https://img.shields.io/badge/Locale-%F0%9F%87%B7%F0%9F%87%BA%20%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0039A6?style=flat-square)
![Português (Brasil)](https://img.shields.io/badge/Locale-%F0%9F%87%A7%F0%9F%87%B7%20Portugu%C3%AAs%20%28Brasil%29-009C3B?style=flat-square)
![Bahasa Indonesia](https://img.shields.io/badge/Locale-%F0%9F%87%AE%F0%9F%87%A9%20Bahasa%20Indonesia-CE1126?style=flat-square)
![Deutsch](https://img.shields.io/badge/Locale-%F0%9F%87%A9%F0%9F%87%AA%20Deutsch-lightgrey?style=flat-square)
![Tiếng Việt](https://img.shields.io/badge/Locale-%F0%9F%87%BB%F0%9F%87%B3%20Ti%E1%BA%BFng%20Vi%E1%BB%87t-DA251D?style=flat-square)
![ไทย](https://img.shields.io/badge/Locale-%F0%9F%87%B9%F0%9F%87%AD%20%E0%B9%84%E0%B8%97%E0%B8%A2-A51931?style=flat-square)
![Bahasa Melayu](https://img.shields.io/badge/Locale-%F0%9F%87%B2%F0%9F%87%BE%20Bahasa%20Melayu-0032A0?style=flat-square)
![Filipino](https://img.shields.io/badge/Locale-%F0%9F%87%B5%F0%9F%87%AD%20Filipino-0038A8?style=flat-square)
![Italiano](https://img.shields.io/badge/Locale-%F0%9F%87%AE%F0%9F%87%B9%20Italiano-008C45?style=flat-square)
![Türkçe](https://img.shields.io/badge/Locale-%F0%9F%87%B9%F0%9F%87%B7%20T%C3%BCrk%C3%A7e-E30A17?style=flat-square)
![Polski](https://img.shields.io/badge/Locale-%F0%9F%87%B5%F0%9F%87%B1%20Polski-DC143C?style=flat-square)
![हिन्दी](https://img.shields.io/badge/Locale-%F0%9F%87%AE%F0%9F%87%B3%20%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-FF9933?style=flat-square)
![Українська](https://img.shields.io/badge/Locale-%F0%9F%87%BA%F0%9F%87%A6%20%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-0057B7?style=flat-square)

Windows 桌面倒數計時器，支援多視窗同時運作、群組連續執行、彈性提醒、語音倒數與通知視窗。常駐系統匣，開箱即用，內建 20 種語言。

---

## 功能說明

### 計時器視窗

每個計時器為獨立視窗，可自由縮放與拖移。視窗顯示：

- 倒數時間（時：分：秒，可開啟小數）
- 進度條與百分比
- 已經過時間（正數計時）
- 預計結束時間
- 操作按鈕（開始 / 暫停 / 停止 / 重啟 / 繼續 / 初始化），以圖示呈現，滑鼠停留可顯示對應文字說明

支援**負計時模式**，歸零後繼續往負數倒數。

### 多視窗管理

- 可同時開啟多個計時器，每個獨立運作
- 相同設定檔可開啟多個實例，標題列自動加上 `#N` 編號
- **自動排列**：一鍵將所有視窗整齊排列於螢幕工作區

### 群組管理

將多個計時器編成一組，依序自動接續執行，適合「連續多階段」的計時情境（例如：休息 → 泡麵 → 蒸蛋 依序倒數）。

- 群組成員依設定順序執行，可用上移／下移調整順序，或用快捷鍵（Delete 移除、Enter 設定循環次數、Alt+↑／Alt+↓ 上移下移）操作
- 每個成員可設定**循環次數**：同一個計時器要連續運行幾次才換下一個
- 整個群組可設定**整輪重複次數**，或開啟無限重複
- **支援巢狀群組**：群組成員本身也可以是另一個群組——巢狀群組被包含進其他群組時，只算它自己成員跑一輪，不套用它自己的整輪重複次數（那個設定只在它被當成最外層、直接執行時才有意義），無限重複因此只會出現在最外層
- **時長試算**：群組管理清單與編輯群組畫面都會即時顯示每個成員、每一輪、以及整個群組（含重複次數後）的預估時長，方便在設定前就知道整體會跑多久
- 編輯群組時可直接對選取的成員按「編輯」，開啟該計時器的設定視窗、或該巢狀群組自己的編輯視窗，不用切到啟動視窗或群組管理清單另外找
- 群組管理清單、編輯群組的成員清單都支援右鍵選單（涵蓋所有操作按鈕的功能）與欄位排序（點擊欄位標題排序，同一欄再點一次反轉方向）
- 編輯群組時若有未儲存的變更，取消或關閉視窗前會先詢問確認，避免誤操作遺失修改
- 群組管理視窗即時顯示各群組狀態（運行中 / 未運行 / 已結束）與成員數
- 可對群組整體執行開始、停止、關閉

### 系統匣

程式常駐系統匣，右鍵選單提供：

- 啟動視窗（LaunchForm）
- 群組管理
- 新增倒數計時器
- 預設計時器設定
- 自動排列計時器
- 關閉所有計時器
- 贊助 / 支持開發
- 分享此 App
- 檢查更新
- 語系切換
- 說明
- 關於
- 結束程式

雙擊系統匣圖示可快速開啟啟動視窗。

### 檢查更新

選單中的「檢查更新」會連線 GitHub 查詢最新 Release 版本並與目前版本比較，有新版本時會詢問是否前往下載頁面。程式啟動後也會延遲數秒自動靜默檢查一次，沒有新版本時不會打擾使用者。

### 說明

選單中的「說明」提供一份內建、離線可看的功能摘要（免連網），視窗底部另外附一個 Ko-fi 連結，可前往查看更完整的說明或教學影片。

### 贊助 / 支持開發、分享此 App

「贊助 / 支持開發」點擊後會開啟瀏覽器前往 Ko-fi 贊助頁面；「分享此 App」則會開啟一個小視窗，準備好一段包含 App 介紹與 GitHub 連結的文字，可一鍵複製後貼到任何聊天工具、社群或論壇分享，或直接點擊連結前往 GitHub 頁面。

### 設定

每個計時器有獨立設定，分為以下頁籤：

底部按鈕列可**複製設定**／**貼上設定**：把目前畫面上的所有欄位（含視窗縮放比例）複製到剪貼簿，再貼到另一個計時器（或批次設定畫面），不用逐項手動調整成一樣的設定；每個顏色欄位旁的「選色」按鈕右側，也各自有獨立的複製／貼上，可以單獨把一種顏色套用到別的顏色欄位。設定視窗若有未儲存的變更，取消或關閉前會先詢問確認。

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
最後 3 / 5 / 10 秒播放語音倒數檔（`Sound_effects\Countdown_voice_XX.wav`），可依目前介面語言提供不同語言的錄音（見下方〈音效檔案〉）。

### 通知視窗

各提醒觸發時，可在螢幕上方彈出無邊框通知視窗，顯示：

- 計時器名稱
- 目前計時時間（AR / AE 會持續更新）
- 自訂通知文字

多個通知視窗會自動排列，從螢幕頂部置中往兩側展開，避免重疊。

### 啟動視窗（LaunchForm）

集中管理所有計時器設定檔，設定檔清單顯示名稱、隨程式啟動狀態、時長與最後修改時間，支援點擊欄位標題排序、右鍵選單，以及 Delete / Enter 快捷鍵。視窗重新取得焦點時（例如剛編輯完某個計時器切回來）會自動刷新清單內容，並保留原本的選取項目。

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
Timers\                  # 計時器設定檔（.ini）與預設設定
  Groups\                 # 群組設定檔（.ini）
Settings\                # 啟動行為、最後開啟紀錄等程式層級設定
Location\                # 視窗位置記錄（.ini）
Sound_effects\           # 自訂音效與語音倒數檔案
  Voice\<語系代碼>\        # 各語言專屬的語音倒數錄音（選用，找不到則自動退回上層預設檔）
Language\                # 多語系語言檔（.ini）
Countdown_Timer.ico      # 自訂圖示（可選）
```

> 舊版（1.x）使用扁平的 `Config\` 資料夾存放設定檔，程式會在啟動時自動偵測並一次性搬移至新的 `Timers\` / `Settings\` 結構，不需手動處理。

## 多語系支援

內建 20 種語言，語系選單依「東亞 → 東南亞 → 南亞／西亞 → 歐洲」分組、組內大致依使用人口排序：

| 語系代碼 | 語言 | 語系代碼 | 語言 |
|---|---|---|---|
| `zh` | 正體中文 | `hi` | हिन्दी |
| `zh-cn` | 简体中文 | `tr` | Türkçe |
| `ja` | 日本語 | `en` | English |
| `ko` | 한국어 | `es` | Español |
| `id` | Bahasa Indonesia | `fr` | Français |
| `fil` | Filipino | `ru` | Русский |
| `vi` | Tiếng Việt | `pt-br` | Português (Brasil) |
| `th` | ไทย | `de` | Deutsch |
| `ms` | Bahasa Melayu | `it` | Italiano |
| | | `pl` | Polski |
| | | `uk` | Українська |

優先使用設定值，若未設定，則根據系統語系自動偵測預設語言。可在系統匣選單的語系子選單中切換，重新啟動後生效。

語言檔位於 `Language\` 目錄，每個語言一個 `.ini` 檔，支援自訂語言檔擴充——新增一個對應語系代碼的 `.ini` 檔即可自動出現在語系選單中，不需修改程式碼。

介面字型會依語系自動調整：泰文（th）與印地文（hi）改用 Windows 內建的原生使用者介面字型（分別為 Leelawadee UI、Nirmala UI），避免疊字母音符號用中日韓字型顯示時過小難辨；其餘語言維持統一字型不變。

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

### 語音倒數的多語系錄音（選用）

語音倒數預設所有語言共用同一組錄音。若想針對特定語言提供對應發音，可在 `Sound_effects\Voice\` 底下建立以語系代碼命名的子資料夾，放入同名 wav 檔，例如：

```
Sound_effects\Voice\vi\Countdown_voice_03.wav
Sound_effects\Voice\vi\Countdown_voice_05.wav
Sound_effects\Voice\vi\Countdown_voice_10.wav
```

程式會依目前介面語言自動尋找對應資料夾，找不到時自動退回 `Sound_effects\` 底下的預設錄音，未提供的語言不受影響。

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

[PolyForm Noncommercial License 1.0.0](Countdown_Timer_License.txt)

本軟體僅授權非商業用途使用。

---

## 作者

林彥丞  
[GitHub](https://github.com/ArtLife-Software) ·
[Facebook 社群](https://www.facebook.com/groups/vba.club) ·
[Ko-fi](https://ko-fi.com/artlifesoftware) ·
lin.yancheng@outlook.com
