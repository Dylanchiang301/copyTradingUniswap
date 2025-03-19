# 🔄 Uniswap Copy Trading Bot

本專案是一個基於 **ethers.js** 和 **Uniswap V2** 的交易跟單功能，可監聽指定錢包地址的交易，並自動複製其交易來取得執行交易的資料。

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Ethers.js](https://img.shields.io/badge/ethers.js-5.7.2-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## **📌 功能介紹**
### ✅ **自動監聽交易**
- 監聽指定的 **EOA 地址 (`TRACK_ADDRESS`)**，當它透過 **Uniswap V2 Router (`UNISWAP_V2_ROUTER_ADDRESS`)** 進行交易時，自動擷取交易資訊。

### ✅ **交易跟單**
- 支援 **ETH 兌換代幣 (`swapExactETHForTokens`)**
- 支援 **代幣兌換 ETH (`swapExactTokensForETH`)**
- 透過 **`copyTradeFromData()`** 解析交易數據，並複製交易到個人帳戶。

### ✅ **動態 Gas 調整**
- 透過即時查詢網絡 Gas 費用，確保交易能快速成功。

### ✅ **交易風控**
- **黑名單機制**：可設定不允許跟單的特定地址。
- **動態計算資金使用**，防止餘額不足。

---

## 📬 聯絡方式
📧 Email: cmydylan@gmail.com

🌐 GitHub: [Dylanchiang301](https://github.com/Dylanchiang301)

