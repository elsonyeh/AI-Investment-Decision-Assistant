<div align="center">

# 🤖 AI投資決策小幫手

**基於 Multi-Agent 架構的智能投資分析系統**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![OpenAI](https://img.shields.io/badge/Powered%20by-OpenAI-412991.svg)](https://openai.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://www.javascript.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

使用 ChatGPT API 提供專業的股票投資分析建議

[功能特色](#-功能特色) • [快速開始](#-快速開始) • [使用方法](#-使用方法) • [費用說明](#-費用說明) • [文檔](#-文檔)

</div>

---

## 📸 專案展示

> **提示：** 您可以在此添加應用截圖，展示系統介面和功能

```
建議添加以下截圖：
1. 主介面（配置區）
2. 分析進度畫面
3. 投資決策摘要
4. 詳細分析報告
```

## 🌟 功能特色

### 📊 Multi-Agent 投資分析架構

本系統採用先進的多智能體架構，模擬真實投資團隊的決策流程：

<table>
<tr>
<td width="50%">

#### 🎯 分析師團隊
- 📈 **技術分析師** - 技術指標、趨勢判斷
- 💼 **基本面分析師** - 財務評估、估值分析
- 📰 **新聞分析師** - 事件追蹤、政策影響
- 💬 **情緒分析師** - 社群情緒、市場動向

</td>
<td width="50%">

#### 🔄 決策流程
- 🐂🐻 **多空辯論** - 雙方論證、風險平衡
- ⚠️ **風險管理** - 等級評估、倉位建議
- 🎯 **組合經理** - 最終決策、目標價位

</td>
</tr>
</table>

### 🌍 多市場支援
| 市場 | 代碼示例 | 說明 |
|------|---------|------|
| 🇺🇸 美股 | `AAPL`, `TSLA`, `MSFT` | 納斯達克、紐約證交所 |
| 🇹🇼 台股 | `2330`, `2317`, `2454` | 台灣證券交易所 |
| 🇭🇰 港股 | `00700`, `09988` | 香港交易所 |

### ⚙️ 靈活配置
- 🎚️ **5級分析深度** - 從快速瀏覽到深度研究
- 🎯 **自選分析師** - 根據需求選擇分析維度
- 📅 **歷史分析** - 回溯任意日期的市場狀況

---

## 🚀 快速開始

### 📋 前置需求

- 現代化瀏覽器（Chrome、Firefox、Safari、Edge）
- OpenAI API Key（[點此獲取](https://platform.openai.com/api-keys)）
- （可選）本地 Web 伺服器（Python、Node.js 等）

### ⚡ 三步驟啟動

#### 1️⃣ 克隆專案

```bash
git clone https://github.com/elsonyeh/AI-Investment-Decision-Assistant.git
cd AI-Investment-Decision-Assistant
```

#### 2️⃣ 配置 API Key

```bash
# 複製配置範例
cp config.example.js config.js

# 編輯 config.js，填入您的 API Key
# OPENAI_API_KEY: 'sk-proj-xxxxxxxxxx',
```

#### 3️⃣ 啟動應用

**方法 A：直接開啟**
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

**方法 B：使用本地伺服器（推薦）**
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server

# 然後訪問 http://localhost:8000
```

---

## 📖 使用方法

### 1. 配置分析參數

| 參數 | 說明 | 示例 |
|------|------|------|
| 市場選擇 | 選擇交易市場 | 美股 / 台股 / 港股 |
| 股票代碼 | 輸入標的代碼 | `TSLA`, `2330`, `00700` |
| 分析日期 | 選擇分析日期 | 預設為今天 |
| 研究深度 | 1-5 級可調 | 建議使用 3 級（標準） |
| 分析師團隊 | 勾選需要的分析師 | 建議全選以獲得全面分析 |

### 2. 查看分析結果

**投資決策摘要**
- 💡 投資建議（買入/持有/賣出）
- 📊 置信度評分（0-100%）
- ⚠️ 風險評分（0-100%）
- 🎯 目標價位

**詳細分析報告**（六大維度）
- 📈 技術面分析
- 💼 基本面分析
- 💬 市場情緒分析
- 📰 新聞事件分析
- ⚠️ 風險評估
- 💡 投資建議

---

## 💰 費用說明

### 📊 API 成本（使用 gpt-4o-mini）

| 分析深度 | 預估費用（USD） | 適用場景 |
|---------|----------------|----------|
| 🟢 1級（快速） | $0.02 - $0.05 | 快速瀏覽、初步篩選 |
| 🟡 3級（標準） | $0.05 - $0.10 | **日常使用（推薦）** |
| 🔴 5級（深度） | $0.10 - $0.20 | 重要決策、深入研究 |

### 💡 省錢技巧

1. ✅ 設置 [OpenAI 使用限制](https://platform.openai.com/account/limits)
2. ✅ 日常使用選擇 3 級分析
3. ✅ 測試時使用 1-2 級
4. ✅ 考慮使用 gpt-4o-mini（已是最便宜的選項）

---

## ⚠️ 重要聲明

### 🔒 安全注意事項

| ❌ 禁止 | ✅ 建議 |
|---------|---------|
| 上傳 `config.js` 到公開平台 | 使用 `.gitignore` 保護 API Key |
| 分享您的 API Key | 定期更換 API Key |
| 在公開場合展示 API Key | 設置使用額度限制 |

### 📉 投資風險聲明

```
⚠️ 重要提示：
• 本系統提供的分析僅供參考，不構成專業投資建議
• AI 分析基於歷史數據，可能存在偏差或錯誤
• 投資有風險，決策需謹慎
• 建議結合其他資訊來源並諮詢專業財務顧問
• 過往表現不代表未來結果
```

---

## 🎨 技術架構

### 前端技術棧
- **HTML5** - 語義化結構
- **CSS3** - 漸層設計、響應式佈局
- **Vanilla JavaScript** - ES6+、Async/Await
- **OpenAI API** - GPT-4o-mini

### 設計理念
- 🎨 **專業藍色系** - 穩重可信賴
- 📱 **響應式設計** - 支援各種裝置
- ⚡ **流暢動畫** - 提升使用體驗
- 🎯 **清晰層級** - 卡片式資訊架構

---

## 🔧 進階設定

### 修改 AI 模型

```javascript
// 在 config.js 中
MODEL: 'gpt-4o',  // 使用更強大的模型（成本較高）
```

### 自訂分析提示詞

```javascript
// 在 script.js 的 callAgentAPI 函數中
// 修改各個 agent 的 prompts 物件
```

### 調整參數

```javascript
// 在 config.js 中
MAX_TOKENS: 3000,     // 獲得更詳細的分析
TEMPERATURE: 0.5,     // 降低創意性，提高準確性
```

---

## 🐛 故障排除

<details>
<summary><b>問題：顯示 "API 調用失敗"</b></summary>

**解決方案：**
1. 檢查 `config.js` 中的 API Key 是否正確
2. 確認 OpenAI 帳戶有足夠餘額
3. 檢查網路連接狀態
4. 查看瀏覽器控制台的詳細錯誤訊息（F12）
</details>

<details>
<summary><b>問題：分析速度很慢</b></summary>

**解決方案：**
1. 降低分析深度（1-2 級）
2. 減少選擇的分析師數量
3. 檢查網路速度
</details>

<details>
<summary><b>問題：分析結果不準確</b></summary>

**可能原因：**
1. ChatGPT 知識截止日期限制（不含最新資訊）
2. 股票代碼輸入錯誤
3. 分析深度不足

**建議：**
1. 增加分析深度到 4-5 級
2. 交叉驗證其他資訊來源
3. 查看詳細報告而非僅看摘要
</details>

---

## 📚 文檔

- 📘 [完整使用手冊](README.md) - 本文件
- ⚡ [快速開始指南](QUICK_START.md) - 5 分鐘上手
- 🔑 [API 配置說明](config.example.js) - API Key 設置
- 📜 [授權條款](LICENSE) - MIT License

---

## 🤝 貢獻指南

歡迎提交 Pull Request 或 Issue！

### 如何貢獻

1. Fork 本專案
2. 創建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的變更 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 開啟 Pull Request

### 開發路線圖

- [ ] 支援更多市場（日股、A股等）
- [ ] 增加技術指標圖表視覺化
- [ ] 批次分析多檔股票
- [ ] 歷史分析結果保存功能
- [ ] 自訂分析師 Agent
- [ ] 支援其他 AI 模型（Claude、Gemini 等）

---

## 📞 聯絡與支援

- 💬 **問題回報**：[GitHub Issues](https://github.com/elsonyeh/AI-Investment-Decision-Assistant/issues)
- 📧 **功能建議**：透過 Issues 提出
- 📖 **OpenAI 文檔**：[platform.openai.com/docs](https://platform.openai.com/docs)

---

## 📄 授權協議

本專案採用 [MIT License](LICENSE) 授權。

**投資風險聲明：** 本軟體僅供教育和研究使用。使用者需自行承擔使用本系統產生的所有風險和責任。

---

## 🙏 致謝

- [OpenAI](https://openai.com/) - 提供強大的 GPT API
- 所有貢獻者和使用者的支持

---

<div align="center">

**🤖 Generated with AI Multi-Agent System**

**Powered by ChatGPT API**

⭐ 如果這個專案對您有幫助，歡迎給個星星！⭐

最後更新：2025-12-16

</div>
