# EUROPE JOURNAL — 歐洲旅遊知識庫 (Innsbruck 2027)

> **專為 2027 年春夏季在奧地利茵斯布魯克大學（University of Innsbruck）交換學生設計的歐洲旅遊指引。**

---

## 專案簡介

EUROPE JOURNAL 是一個結合歐美旅遊雜誌風格（Travel Editorial）與高度實用性的歐洲旅遊知識庫。以奧地利提洛邦首府茵斯布魯克（Innsbruck）為出發核心，協助預算有限、時間受限的交換學生在 2027 年 2 月至 7 月期間，平衡學期課業、期末考試與預算，探索全歐精華目的地。

---

## 核心特色與原則

1. **以 Innsbruck 為交通樞紐（Hub-Centric）**：善用 ÖBB 奧地利國鐵、Nightjet 臥鋪、跨國高速鐵路與 Munich (MUC) / Innsbruck (INN) 機場，精選 2–3 天週末行程與長假路線。
2. **注重預算與體驗平衡（Budget-Conscious Quality）**：不盲目追求最低價窮遊，為學生精算交通套票（Vorteilscard 66、Klimaticket、Eurail）、優質青旅與門票優惠。
3. **對齊學期節奏與氣候（Season-Aware）**：全盤考量 2 月阿爾卑斯雪季到 7 月盛夏地中海氣候，並特別規劃避開 5–6 月密集考試週。
4. **真實可靠的資訊（Reliable Information）**：所有交通、花費、開放時間均經查核；資訊無法確定時明確標示。

---

## 專案結構

本網站為相容於 GitHub Pages 的純靜態網站：

```text
europe_travel/
├── index.html          # 網站首頁（雜誌封面、三大原則、目的地導覽、旅行指南、2027 季節日曆、Innsbruck 基地）
├── AGENTS.md           # AI 協同開發規範與標準
├── README.md           # 專案介紹與架構說明
├── css/
│   └── style.css       # 全站共用樣式（米白、深藍、低飽和棕色旅遊雜誌風排版）
├── js/
│   └── main.js         # 共用互動腳本（行動版導覽、目的地分區篩選、平滑滾動、回到頂端）
├── pages/              # 各國與城市詳細介紹頁（依照 AGENTS.md 標準模板陸續新增）
└── images/             # 靜態影像素材目錄
```

---

## 本地預覽

直接在瀏覽器中開啟 `index.html`，或使用任何靜態網頁伺服器（例如 Live Server 或 Python HTTP Server）：

```bash
python -m http.server 8000
```

並在瀏覽器前往 `http://localhost:8000` 即可預覽。
