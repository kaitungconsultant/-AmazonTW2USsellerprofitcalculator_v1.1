# 🇺🇸 Amazon 美國站 FBA 成本計算機 | 台灣賣家專用

專為台灣賣家設計的 Amazon FBA 成本與利潤分析工具。純前端、零依賴、開箱即用。

費率資料來源：
- [Amazon 全球開店官方費率頁](https://gs.amazon.com.tw/pricing)
- [Amazon 全球開店官方優惠頁](https://gs.amazon.com.tw/benefits)

## ✨ 功能

- 💰 **品類佣金自動帶入** — 選擇品類自動套用正確佣金比例，支援階梯費率
- 📦 **FBA 配送費自動估算** — 依商品重量與尺寸自動判斷 Size Tier 並計算費用
- 🏭 **FBA 倉儲費計算** — 支援淡季/旺季切換（$0.78 vs $2.40/cuft）
- 🚚 **Inbound Placement 費** — 依尺寸分級自動估算入倉配置費
- 💳 **帳戶月費分攤** — $39.99 專業計畫月費依銷量分攤到每件
- 🔄 **退款管理費** — 自動計算 min(佣金×20%, $5.00)
- 💱 **台幣/美金即時匯率查詢**
- 📊 **成本結構視覺化** — 比例條圖一眼看出成本分佈
- 📈 **售價情境分析表** — 不同售價下的利潤、利潤率、ROI 對比
- 📋 **費率速查表** — FBA 配送費率 & 品類佣金一覽

### 🎁 新賣家優惠模擬（新功能）

- **新賣家入門大禮包** — 勾選即可模擬帳戶月費減免、$200 廣告金、$100 Coupon、$200 Vine、$100 FBA 運費金、Brand Bonus 10% 回饋
- **FBA 物流新選品計畫** — 勾選即可模擬免倉儲費 120 天、免退貨處理、10% 銷售回饋、Vine 75 折、免 Inbound Placement 費
- 兩個方案可疊加使用，計算機會自動將節省金額反映在利潤分析中

## 🚀 使用方式

### 直接開啟
下載 `index.html`，用瀏覽器打開即可。

### GitHub Pages 部署
1. Fork 這個 repo
2. Settings → Pages → Source 選 `main` branch
3. 上線網址：`https://你的帳號.github.io/amazon-cost-calculator/`

## ⚠️ 注意事項

- FBA 費用為估算值，實際費用依商品尺寸重量而定
- 建議搭配 [Amazon Revenue Calculator](https://sellercentral.amazon.com/hz/fba/profitabilitycalculator/index) 交叉驗證
- 優惠方案有資格條件和時間限制，詳情請見 [Amazon 全球開店優惠頁](https://gs.amazon.com.tw/benefits)
- 匯率查詢使用免費 API，僅供參考
- 本工具不收集任何使用者資料

## 📄 License

MIT License - 自由使用、修改、分享。
