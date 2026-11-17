# 吳芳瑜｜軟體工程師作品集

一頁式個人作品集，讓面試官透過單一網址瀏覽兩個專案的技術、分工與展示連結。

## 線上展示

GitHub Pages 部署完成後：`https://kikiwu853.github.io/portfolio/`

## 收錄專案

### 1. Gym CRM｜健身房管理系統（團隊專題）

- 程式碼：[GymProject](https://github.com/kikiwu853/GymProject)
- 技術：Java 21、Spring Boot、React、SQL Server、REST API
- 我的負責範圍：會員課程預約、我的預約查詢／修改／取消、教練課表管理、管理員全館排程，以及預約模組前後端串接。
- 此專案由 **5 人團隊共同開發**，未公開部署完整系統；作品集連結指向 README 與原始碼。

### 2. 永樂街鱔魚麵｜店家介紹網站（個人作品）

- [線上網站](https://kikiwu853.github.io/restaurant/) · [程式碼](https://github.com/kikiwu853/restaurant)
- 技術：HTML、CSS、JavaScript、Bootstrap 5
- 包含響應式版面、圖片輪播、菜單、Google Maps、美食扭蛋機及表單互動。
- 聯絡表單僅為前端示範，不會真正寄信。

## 專案檔案

```text
portfolio/
├── index.html
├── assets/
│   └── favicon.svg
├── .nojekyll
└── README.md
```

`index.html` 內含網站樣式，不需要安裝套件或建置工具。兩張專案圖片均從對應的公開 GitHub Repository 讀取，不用額外上傳二進位圖片。

## 部署到 GitHub Pages

1. 在 GitHub 建立 **Public** Repository：`portfolio`，建立時不需額外新增 README。
2. 將本資料夾內的 `index.html`、`README.md`、`.nojekyll`、`assets/` 上傳到 Repository 根目錄。
3. 開啟 **Settings → Pages**，設定 **Deploy from a branch → main → /(root)**，儲存。
4. GitHub Actions 顯示部署成功後，訪問 `https://kikiwu853.github.io/portfolio/`。

## 維護

- 更新專案資訊、技術與連結：編輯 `index.html`。
- 更新餐廳網站圖片：調整 `index.html` 中引用的餐廳 GitHub 原圖網址。
- 若 Gym CRM 圖片在 GitHub 被移動，更新 `index.html` 中的 `raw.githubusercontent.com` 圖片 URL。