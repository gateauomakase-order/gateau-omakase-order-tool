# 🎂 Gateau Omakase - 一鍵入單工具

這是一個為 **Gateau Omakase** 設計的自動化訂單管理系統。客人填寫訂單後，只需一鍵傳送，系統會自動將資料同步到 Google Sheets 和 Google 日曆。

## 🚀 功能特點

✅ **一鍵入單**：將 WhatsApp 訂單訊息貼入，自動解析並傳送  
✅ **自動同步**：資料即時出現在 Google Sheets  
✅ **日曆提醒**：標記「已付」後自動在 Google 日曆建立取貨日程  
✅ **iPhone 友善**：支持「加入主畫面」變成桌面應用  
✅ **永久免費**：託管在 GitHub Pages，永久有效

## 📱 iPhone 使用方法

1. 用 Safari 打開本網站
2. 點擊下方分享按鈕 (📤)
3. 選擇「加入主畫面」
4. 命名為「🎂 入單工具」
5. 點擊「新增」

完成！你的 iPhone 桌面就會出現一個專屬應用圖示。

## 📋 訂單格式

系統會自動解析以下格式的訂單：

```text
【Gateau Omakase 訂單確認】

1. 入數日期：(YYYY/MM/DD)
2. 客人名稱：
3. 選購項目：
4. 聯絡電話：
5. 取貨日期：(YYYY/MM/DD)
6. 取貨時間：(1300-1400)
7. 取貨方法：(自取 / 步兵 / 的士代送)
8. 送貨地址：(如需送貨請填寫)
9. 金額明細：
10. 總金額：
11. 保溫袋：(需要 / 不需要)
12. Message 內容：
```

## 🔗 整合系統

本工具透過 **Make.com** 與以下系統整合：

- **Google Sheets**：自動記錄所有訂單和會計資料
- **Google 日曆**：自動生成取貨日程提醒
- **Google Apps Script**：自動同步日期和時間

## 💡 技術棧

- **前端**：HTML5 + CSS3 + Vanilla JavaScript
- **託管**：GitHub Pages (永久免費)
- **自動化**：Make.com Webhook + Google Apps
- **資料庫**：Google Sheets

## 📞 支持

如有任何問題或建議，請聯絡 Manus 支持團隊。

---

**祝你生意興隆！🎂✨**
