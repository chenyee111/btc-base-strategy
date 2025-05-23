# 📊 BTC BOLL 策略 v4

基於 TradingView 的 Pine Script v6 編寫，這是一套適用於 BTC 合約交易的區間策略。具備盈虧平衡線提示、固定風控設計、補倉與追蹤止損等功能，適用於 15min～1h 震盪盤操作。

---

## ✨ 策略特色

| 模組 | 說明 |
|------|------|
| ✅ 固定開倉 + 補倉 | 首倉 3%，補倉 2%，總倉位不超過 5% |
| 📉 BOLL 通道策略 | 價格跌破下軌做多，突破上軌做空 |
| 🔁 自動補倉 | 首倉偏離 ±100 點時補倉一次 |
| 🟠 盈虧平衡線提示 | 槓桿條件下 +188 點才真正盈 |
| 🎯 固定停利 + 追蹤止損 | 出場點可自訂：+300、trail +200 |
| 🧠 適用場景 | BTC 震盪區間操作 / 假突破交易 |

---

## 💡 策略圖示預覽

> 可上傳圖檔：策略回測曲線、BOLL 線圖、盈虧分水線等

---

## 🔧 使用方式

1. TradingView → 新增策略頁籤
2. 貼上 `btc_boll_strategy_v4.pine` 程式碼
3. 選擇週期（建議：15m 或 1h）
4. 啟動回測、觀察區間邏輯是否觸發

---

## 📌 策略參數建議

| 參數 | 建議值 | 說明 |
|------|--------|------|
| BOLL 週期 | 20 | 適中靈敏度 |
| BOLL 倍數 | 2.0 | 標準布林軌道寬度 |
| 固定停利 | 300 | 槓桿後確保盈餘 |
| 固定止損 | 200 | 嚴格風控 |
| 盈虧平衡線 | 188 | 對應 100x 槓桿成本 |

---

## 👤 作者資訊

策略開發者：[@chenyee111](https://github.com/chenyee111)  
授權：MIT License  
歡迎 Fork、Star、共筆或做測試策略改版 ✨
