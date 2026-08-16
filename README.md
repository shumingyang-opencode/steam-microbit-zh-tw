# STEAM × Micro:bit 繁中教學站

把 **STEAM 教學法**（PBL、5E、教案與評量設計）與 **BBC Micro:bit 動手實作**（MakeCode / MicroPython）做成系統化深度教學。每個單元都附可照做的**專案範例**與**教案片段**，讓「理論」變成「明天就能上的一堂課」。

- 目標讀者：STEAM 教師、課程設計者、家長、自學者
- 單元數：20 深度單元（L0 → L5）
- 授權：本站內容 CC-BY-4.0
- 網站：[https://shumingyang-opencode.github.io/steam-microbit-zh-tw/](https://shumingyang-opencode.github.io/steam-microbit-zh-tw/)

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
├── assets/site.css       # 單一共享樣式
└── .nojekyll
```

## 單元列表（20 單元）

| Lv | 單元 | 內容 | STEAM 主軸 |
|----|------|------|-----------|
| L0 | 1 | 概論：STEAM × Micro:bit 為什麼 | — |
| L0 | 2 | Micro:bit 硬體認識（v2 版型、感測器群） | T/E |
| L0 | 3 | 程式環境：MakeCode 與 MicroPython | T |
| L1 | 4 | LED 矩陣與輸出（圖案/動畫/文字） | T+A |
| L1 | 5 | 輸入與感測器（按鈕/加速度/光/溫/麥克風） | S+T |
| L1 | 6 | 事件程式設計與狀態機 | T |
| L1 | 7 | STEAM 教學法一：PBL 與 5E | 教學法 |
| L2 | 8 | 科學專案：資料收集與記錄 | S |
| L2 | 9 | 工程專案：外接硬體 | E |
| L2 | 10 | 數學應用（隨機/座標/角度/統計） | M |
| L2 | 11 | 科技整合：無線電與群組通訊 | T |
| L2 | 12 | 數位藝術：音樂與 LED 動畫 | A |
| L3 | 13 | 綜合專案一：環境感測站 | S+T+M |
| L3 | 14 | 綜合專案二：互動遊戲設計 | E+A+T |
| L3 | 15 | 專案式學習設計：從主題到教案 | 教學法 |
| L4 | 16 | 教案設計：STEAM 教案結構 | 教學法 |
| L4 | 17 | 班級經營與差異化教學 | 教學法 |
| L4 | 18 | 評量設計：Rubric 與學習歷程 | 教學法 |
| L5 | 19 | 完整案例：一個學期課程藍圖 | 整合 |
| L5 | 20 | 擴充與生態：AI 時代的 STEAM | 整合 |

## 開發

本站為純靜態 HTML，內容由 `/tmp/opencode/steam_site/` 的內容模組生成，無建置步驟。

```sh
# 本機預覽（擇一）
python3 -m http.server 8000
npx serve .
```

## 授權

本站教學內容（繁體中文解說）為本站原創，採 CC-BY-4.0；Micro:bit 硬體資訊與 MakeCode 說明引用自 BBC micro:bit 與 Microsoft MakeCode 之公開資訊。

## 相關連結

- 學習路徑建議服務：[learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
