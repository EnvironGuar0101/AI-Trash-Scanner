# AI-Trash-Scanner

這是一個基於 YOLOv8 的垃圾分類辨識系統，目前部署於 Hugging Face 雲端環境。

## 功能特點
- 使用 **YOLOv8** 進行影像辨識。
- 與 **Firebase Realtime Database** 連動，實現跨平台通訊。
- 支援手機網頁拍照辨識，並將結果回傳至 Unity。

## 檔案說明
- `app.py`: 主要辨識邏輯與 Firebase 監聽腳本。
- `requirements.txt`: 運行所需的 Python 環境依賴。
- `best.pt`: 訓練完成的垃圾辨識模型權重。
