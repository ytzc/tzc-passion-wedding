# 💍 tzc-passion-wedding

2026/2/7 大直典華婚宴 子擎 & 佩璇

## 📖 專案說明

這是一個為婚禮準備的工作管理網站，包含多個功能頁面，幫助婚禮工作團隊更好地協調與執行各項任務。

## ✨ 功能頁面

- **📋 婚禮工作頁面索引** - 主頁面，提供所有功能頁面的快速入口與搜尋功能
- **✅ 婚禮工作分配清單** - 工作分組、物品清單、注意事項
- **⏰ 婚禮時間流程＋任務表** - 當日時間軸與每時段負責人與工作重點
- **👥 每人任務清單** - 每位工作人員的二欄快速任務清單（便於列印）
- **🎤 新郎致詞 (舞台口袋版)** - 致詞稿，可列印為 PDF
- **🪑 座位安排 (A3 打印版)** - 桌位分配、素食標記與帶位表

## 🌐 線上瀏覽

透過 GitHub Pages 瀏覽：

👉 **https://ytzc.github.io/tzc-passion-wedding/**

## 💻 本地開發

### 方法一：直接開啟

直接用瀏覽器開啟 `docs/index.html` 檔案。

### 方法二：使用簡單伺服器

```bash
# 進入 docs 目錄
cd docs

# 使用 Python 啟動簡單伺服器
python -m http.server 8000

# 然後在瀏覽器開啟 http://localhost:8000
```

### 方法三：使用 npx

```bash
# 在 docs 目錄下執行
npx serve docs
```

## 📂 檔案結構

```
tzc-passion-wedding/
├── docs/                              # GitHub Pages 發布目錄
│   ├── index.html                    # 主索引頁
│   ├── wedding_checklist.html        # 工作分配清單
│   ├── wedding_timeline_tasks.html   # 時間流程任務表
│   ├── wedding_person_tasks.html     # 每人任務清單
│   ├── wedding_speech_pdf.html       # 新郎致詞
│   ├── seating.html                  # 座位安排
│   ├── lyrics_card_pdf.html          # 歌詞卡
│   ├── 👔 男方帶位表.pdf
│   ├── 👰 女方帶位表.pdf
│   └── 大直典華閣樓15桌圖.jpg
└── README.md                          # 專案說明文件
```

## ⚙️ GitHub Pages 設定

1. 前往 GitHub 倉庫的 **Settings** > **Pages**
2. 在 **Source** 部分選擇 **Deploy from a branch**
3. 在 **Branch** 選擇 `main` 分支和 `/docs` 資料夾
4. 點擊 **Save** 儲存設定
5. 等待幾分鐘後，網站就會發布到 `https://ytzc.github.io/tzc-passion-wedding/`

## 📝 使用說明

1. 開啟主頁面（index.html）
2. 使用搜尋框可以快速找到相關功能（支援搜尋人名、物品、時間）
3. 點擊「開啟」按鈕查看各功能頁面
4. 點擊「複製連結」可以分享特定頁面給工作人員
5. 點擊「顯示 QR」可以產生 QR Code 方便手機掃描

## 🎊 活動資訊

- **日期**：2026 年 2 月 7 日
- **地點**：大直典華閣樓廳
- **時段**：午宴
- **桌數**：15 桌
- **人數**：158 人

---

Made with ❤️ for 子擎 & 佩璇's Wedding
