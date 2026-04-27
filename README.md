# 📚 Hannah's English Learning

55 歲 Hannah 嘅英文學習專案 — 個人化課程 · 廣東話教學 · Week 1 基礎激活

## 🌐 網上使用

**GitHub Pages URL:** `https://<YOUR-USERNAME>.github.io/hannah-english/`

（`<YOUR-USERNAME>` 要換做你嘅 GitHub username）

## 🎯 係咩

呢個 repo 係為 Hannah（55 歲，退休，喺英國）設計嘅英文學習工具。唔係通用 app，係**針對佢個人情況嘅 curriculum**：
- 完成咗 A1 但需要「激活」
- 廣東話為主嘅學習指引
- 55 歲嘅字體需求（大、清晰）
- 實際英國生活情境

## 📂 Repo 結構

```
hannah-english/
├── index.html                        ← 主頁（3-tab SPA 工具介面 + 課堂入口）
├── tools/                            ← 日常溫習工具
│   ├── flashcard.html                  🃏 閃卡溫習
│   ├── test.html                       📝 進度測驗
│   └── qa-drill.html                   🎯 Q&A 反應訓練
├── lessons/                          ← 5 堂正式課程
│   ├── placement-test.html           ★ 入學評估
│   ├── lesson1-introduction.html     1. 自我介紹
│   ├── lesson2-greetings.html        2. 問候語
│   ├── lesson3-goodbyes.html         3. 告別禮貌
│   ├── lesson4-questions.html        4. 問簡單問題
│   └── lesson5-week1-review.html     5. Week 1 綜合評估
├── teacher/                          ← 老師教案 PDF
│   ├── month1-curriculum.pdf           📅 第一個月大綱
│   ├── lesson1-plan.pdf
│   ├── lesson2-plan.pdf
│   ├── lesson3-plan.pdf
│   ├── lesson4-plan.pdf
│   └── lesson5-plan.pdf
└── README.md
```

## 🃏 3 個溫習工具（主頁 tabs）

| Tab | 功能 | 用途 |
|-----|------|------|
| 🃏 **Flashcard** | 閃卡 / 聽力 / 反向 3 模式 | 記憶訓練，每日 5 分鐘 |
| 📝 **進度測驗** | 20 題 · 4 部分 | 睇下學到幾多 |
| 🎯 **Q&A Drill** | 聽問題 → 即刻答 | 訓練自動反應 |

## 📖 Week 1 · 5 堂課程

涵蓋 24+ 個日常套語：
- **Lesson 1** 自我介紹（5 句）
- **Lesson 2** 問候語（11 句）
- **Lesson 3** 告別禮貌（8 句）
- **Lesson 4** 問簡單問題（5 句）
- **Lesson 5** Week 1 綜合評估 + roleplay

## 📱 裝置支援

- ✅ 桌面瀏覽器（1366×768+）
- ✅ iPhone 17 Pro Max（430×932）
- ✅ 響應式設計，iPad 都用到
- ✅ 可以加去 iOS 主畫面做 PWA-like experience

## 🛠️ Tech Stack

- 純 HTML / CSS / JavaScript（冇 build step，冇 dependencies）
- Web Speech API（文字轉語音，en-GB）
- localStorage（記錄進度，跨 session）
- CSS Grid + Flexbox（響應式 layout）
- Google Fonts: Fraunces (serif), Noto Sans HK (CJK)

## 🚀 本地用

```bash
# Clone
git clone https://github.com/<YOUR-USERNAME>/hannah-english.git
cd hannah-english

# 開 index.html 喺瀏覽器（Mac）
open index.html

# 或者開 local server（recommended，避免 CORS 問題）
python3 -m http.server 8000
# 然後喺瀏覽器打開 http://localhost:8000
```

## 📜 License

個人學習專案 · MIT License
