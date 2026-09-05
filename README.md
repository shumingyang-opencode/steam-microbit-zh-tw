# STEAM × Micro:bit 繁中教學站

把 **STEAM 教學法**（PBL、5E、教案與評量設計）與 **BBC Micro:bit 動手實作**（MakeCode / MicroPython）做成系統化深度教學。每個單元都附可照做的**專案範例**與**教案片段**，讓「理論」變成「明天就能上的一堂課」。

**本站特色：**
- 🎨 **兒童友善設計**：淺色明亮色調，適合 6-9 歲閱讀
- 🔤 **自動注音**：所有中文自動帶注音符號（ㄅㄆㄇㄈ），邊看注音邊學
- 🔊 **語音朗讀**：點擊右下角 🔊 按鈕，支援中英文自動切換朗讀
- 📚 **20 深度單元**：從基礎到進階，每單元含 Worked Example 與練習

- 目標讀者：STEAM 教師、課程設計者、家長、自學者
- 單元數：20 深度單元（L0 → L5）
- 授權：本站內容 CC-BY-4.0
- 網站：[https://shumingyang-opencode.github.io/steam-microbit-zh-tw/](https://shumingyang-opencode.github.io/steam-microbit-zh-tw/)

---

## 功能特色

### 兒童友善設計
- 淺色明亮背景，減少視覺疲勞
- 圓潤卡片設計，親切可愛
- 大字型（18px）+ 寬行高（1.8），適合低年級閱讀
- 彩虹色系（藍、粉、琥珀、翡翠、紫），活潑不刺眼

### 自動注音字型
- 使用 **BpmfIansui**（注音芫荽）字型
- 所有中文自動在右側顯示注音符號
- 例如：「STEAM」→ ㄙˋ ㄊㄧˋ ㄜˋ ㄞˋ ㄇㄨˋ
- 幫助 6-9 歲學童邊看注音邊認字

### 語音朗讀（L3 智慧跟讀）
- 🔊 右下角浮動按鈕，點擊展開控制面板
- ▶ 播放 / ⏸ 暫停 / ⏹ 停止
- 🔊 語速調整（0.5x – 2x）
- 🎤 語音選擇（zh-TW / en-US 多種語音）
- 📝 **段落高亮跟讀**：朗讀時當前段落黃色高亮
- 🌐 **中英文自動切換**：遇中文用中文語音，遇英文用英文語音
- ⌨️ 快捷鍵：`Space` 播放/暫停、`Esc` 停止

---

## 網站結構

```
steam-microbit-zh-tw/
├── index.html            # 課程總覽 + 入口卡片
├── map.html              # 概念地圖：STEAM 五領域 × Micro:bit
├── learning-path.html    # 學習路線：L0 → L5 六層
├── glossary.html         # 📖 術語表
├── hardware.html         # 🔌 硬體速查（感測器/擴充/接腳/周邊）
├── projects.html         # 🛠️ 專案速查（20+ 動手專案一覽）
├── about.html            # 關於本站
├── docs/                 # 單元教學頁
│   ├── index.html        # 單元一覽
│   └── unit-01.html … unit-20.html
├── assets/
│   ├── site.css          # 兒童版樣式（淺色 × 注音）
│   ├── speech.js         # 語音朗讀核心（中英切換）
│   ├── speech.css        # 語音控制面板 UI
│   └── fonts/
│       └── BpmfIansui-Regular.ttf  # 注音芫荽字型
└── .nojekyll
```

---

## 單元列表（20 單元）

| Lv | 單元 | 內容 | STEAM |
|----|------|------|-------|
| L0 | 1 | 概論：STEAM × Micro:bit 為什麼 | 🎯 |
| L0 | 2 | Micro:bit 硬體認識（v2 版型、感測器群） | 🔧⚙️ |
| L0 | 3 | 程式環境：MakeCode 與 MicroPython | 💻 |
| L1 | 4 | LED 矩陣與輸出（圖案/動畫/文字） | 💻🎨 |
| L1 | 5 | 輸入與感測器（按鈕/加速度/光/溫/麥克風） | 🔬💻 |
| L1 | 6 | 事件程式設計與狀態機 | 💻 |
| L1 | 7 | STEAM 教學法一：PBL 與 5E | 📚 |
| L2 | 8 | 科學專案：資料收集與記錄 | 🔬 |
| L2 | 9 | 工程專案：外接硬體 | ⚙️ |
| L2 | 10 | 數學應用（隨機/座標/角度/統計） | 🔢 |
| L2 | 11 | 科技整合：無線電與群組通訊 | 💻 |
| L2 | 12 | 數位藝術：音樂與 LED 動畫 | 🎨 |
| L3 | 13 | 綜合專案一：環境感測站 | 🔬💻🔢 |
| L3 | 14 | 綜合專案二：互動遊戲設計 | ⚙️🎨💻 |
| L3 | 15 | 專案式學習設計：從主題到教案 | 📚 |
| L4 | 16 | 教案設計：STEAM 教案結構 | 📚 |
| L4 | 17 | 班級經營與差異化教學 | 📚 |
| L4 | 18 | 評量設計：Rubric 與學習歷程 | 📚 |
| L5 | 19 | 完整案例：一個學期課程藍圖 | 🔗 |
| L5 | 20 | 擴充與生態：AI 時代的 STEAM | 🔗 |

---

## 開發

本站為純靜態 HTML，無建置步驟。

```sh
# 本機預覽（擇一）
python3 -m http.server 8000
npx serve .
```

### 本機預覽語音功能

語音朗讀功能使用 Web Speech API，需在 HTTP 環境下測試：
1. 啟動本地伺服器：`python3 -m http.server 8000`
2. 開啟瀏覽器：`http://localhost:8000`
3. 點擊右下角 🔊 按鈕測試語音功能

---

## 授權

本站教學內容（繁體中文解說）為本站原創，採 CC-BY-4.0；Micro:bit 硬體資訊與 MakeCode 說明引用自 BBC micro:bit 與 Microsoft MakeCode 之公開資訊。

注音字型 BpmfIansui 採 Apache 2.0 授權，由 ButTaiwan 開發。

---

## 相關連結

- [learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
- [Microsoft MakeCode](https://makecode.microbit.org) — 官方 MakeCode 編輯器
- [BBC micro:bit](https://microbit.org) — 官方硬體文件
