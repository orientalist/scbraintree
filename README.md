# 專案名稱
SurveyCake x Braintree 整合範例

## 簡介
這是一個示範網站，透過 Braintree API 整合支付功能，讓使用者可以在購物車中填寫個人資訊並進行結帳。使用者可以透過這個範例快速了解如何使用 Braintree 進行安全的網上付款。

## 功能
- 顯示買家資訊（姓名、電話、Email）
- 列表展示商品資料，包括名稱、數量、單價與小結
- 根據商品的總金額自動計算並顯示
- 使用 Braintree 的 Drop-in UI 進行支付處理
- 提供結帳功能，提交支付資料給後端伺服器

## 安裝與使用方式
1. 下載或克隆此專案至本地環境。
2. 確保您已有可運行的網頁伺服器（如 Apache 或 NGINX）。
3. 將專案檔案放置於伺服器的根目錄或適當的子目錄。
4. 開啟瀏覽器並輸入相應的網址以查看網頁。
5. 在網址中加入 `?svid=<你的SVID>&hash=<你的HASH>`，以便於獲取相關的資料。

## 必要的依賴模組清單
- [Bootstrap](https://getbootstrap.com/) （版本 5.1.0）: 用於快速設計響應式網頁。
- [Braintree](https://www.braintreepayments.com/) （Drop-in UI，版本 1.31.0）: 用於支付處理。

## 授權條款
本專案採用 MIT 授權條款，詳細內容請參考 LICENSE 檔案。