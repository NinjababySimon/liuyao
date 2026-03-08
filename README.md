# 六爻卜卦 App

依《黃金策》分類的六爻占卜工具，純前端單頁應用，無需伺服器、無需 API。

## 功能

- 🔮 起卦輸入（支援老陽/老陰動爻）
- 📅 自動計算農曆日干支、月干支
- 🀄 自動推算六親、納甲地支、六神（六獸）
- 🌙 空亡、月破自動標示
- 👻 伏神自動推算
- 📖 依《黃金策》15大類別給出占斷分析與結論：
  - 天時、年時、婚姻、求財、功名仕途、求職謀事
  - 行人音訊、出行遠行、疾病、訴訟官非、買賣交易
  - 求子嗣、宅舍居住、六畜牲口、尋人走失

## 使用方式

直接開啟 `index.html`，或部署至 GitHub Pages 即可使用。

## 部署至 GitHub Pages

1. 建立新的 GitHub repository
2. 上傳 `index.html`（可改名，但 GitHub Pages 預設讀取 `index.html`）
3. 在 repository 設定中啟用 **GitHub Pages**，來源選 `main` branch
4. 訪問 `https://<你的帳號>.github.io/<repository名稱>/`

## 技術說明

- 純 HTML / CSS / JavaScript，無任何外部依賴（除 Google Fonts）
- 所有占卜邏輯本地運算，不呼叫任何 API
- 支援手機與桌面瀏覽器
