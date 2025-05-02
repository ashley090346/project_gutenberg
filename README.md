# Project Gutenberg 中文書籍爬蟲

本專案用於爬取 [Project Gutenberg](https://www.gutenberg.org/) 上的中文書籍，已成功爬取 **共 353 本** 書籍，並儲存為 `.txt` 檔案格式。

---

## 📦 安裝套件

本專案需使用以下 Python 套件，可使用 `pip install` 安裝：

- `requests` (2.32.3)
- `beautifulsoup4` (4.13.4)
- `lxml` (5.4.0)


建議使用虛擬環境安裝：
```bash
pip install requests==2.32.3 beautifulsoup4==4.13.4 lxml==5.4.0 selenium
```

Python 版本需求：**3.9.12**

---

## ▶️ 執行方式

1. 確保已安裝 Chrome 瀏覽器與相容版本的 ChromeDriver。
2. 開啟 `gutenberg.ipynb`，逐格執行程式碼即可啟動爬蟲。
3. 所有書籍將自動儲存在 `project_gutenberg/` 資料夾內，以 `.txt` 格式保存，檔名為書籍名稱。

---

## 📁 專案結構

```
WEB_SCRAPING_HW/
├── project_gutenberg/      # 儲存爬取的書籍 txt 檔案
├── gutenberg.ipynb         # 主爬蟲程式（Jupyter Notebook）
└── README.md               # 專案說明檔
```

---

## 🖼️ 成果展示

以下為執行過程與爬取成果示意圖：

🎬 [完整影片展示](https://youtu.be/A_zoroDkV-0)

---

## ⚠️ 注意事項

- Gutenberg 網頁架構若有更動，需手動調整 HTML 解析邏輯。
- 若遇到亂碼或無法顯示的文字，請確認 `.txt` 檔案以 UTF-8 編碼儲存。

---

## 📚 書籍來源

資料來源：  
🔗 [Project Gutenberg 中文書籍列表](https://www.gutenberg.org/browse/languages/zh)

---

## ✅ 總結

- 爬取總數：**353 本**
- 存檔格式：`.txt`
- Python 環境：`3.9.12`
- 使用工具：`requests`、`beautifulsoup4`、`lxml`

