# 鐵皮額度與護角庫存自動化儀表板

本專案旨在自動化讀取 Excel 報表（支援 `.xlsx` 與 `.xls`），過濾隱藏欄列與錯誤值，並轉換產出符合一致性檢查的離線單頁 Dark Mode HTML 儀表板，無須依賴外部網路即可檢視。

---

## 📁 專案目錄結構

- `input/`：存放原始 Excel 檔案的資料夾（如鐵皮採購額度、護角分條庫存等）
- `output/`：程式執行後自動輸出產出的 HTML 儀表板檔案位置
- `main.py`：核心解析與 HTML 生成主程式
- `requirements.txt`：Python 套件相依性清單
- `README.md`：專案說明文件

---

## ⚙️ 環境需求與安裝步驟

在 Codespaces 終端機（Terminal）中依序執行以下指令來安裝相依套件：

1. 確保已安裝專案所需的 Python 套件：
   ```bash
   pip install -r requirements.txt