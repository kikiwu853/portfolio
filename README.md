# 吳芳瑜｜Java 軟體工程師作品集

> 從社會工作跨領域轉職軟體開發，以實際專案累積前後端整合、資料庫應用與使用者流程設計經驗。

**[個人作品集網站](https://kikiwu853.github.io/portfolio/)** ｜ [GitHub 個人首頁](https://github.com/kikiwu853)

> 作品集網站使用 GitHub Pages；如暫時無法開啟，請先由本 README 查看下方專案連結。Gym CRM 目前提供程式碼與本機展示說明，尚無公開線上操作版本。

## 關於我

過去具有社會工作及青少年服務經驗，習慣從使用者需求出發，釐清流程、溝通問題並整合資訊。完成 Java 軟體工程師培訓後，透過 **Gym CRM 全端團隊專題**及**永樂街鱔魚麵個人前端作品**，實作網站介面、REST API、資料庫查詢與互動功能。

目前以 **Java 後端／全端軟體工程師**為求職方向，持續強化程式設計、系統整合與問題排查能力。

## 技術能力

| 分類 | 技術與工具 |
| --- | --- |
| 後端開發 | Java 21、Spring Boot、Spring MVC、Spring Data JPA、REST API |
| 前端開發 | React、JavaScript、HTML5、CSS3、Bootstrap、Vite |
| 資料庫 | SQL Server、SQL、資料表關聯設計 |
| 開發與協作 | Git、GitHub、Maven、Postman、Eclipse、SSMS |

## 精選專案

### 01｜Gym CRM 健身房管理系統

**專案類型：** 5 人團隊全端專題  
**技術：** Java 21、Spring Boot、React、SQL Server、Spring Data JPA、REST API

將會員、教練與管理員的操作流程整合至健身房管理系統。我主要負責**三端預約相關功能**，並參與前後端串接與整合：

- **會員端：** 依已購課程與可預約時段建立預約；查詢、改期、取消及查看歷史紀錄。
- **教練端：** Dashboard 與課表查詢、日期切換、預約管理。
- **管理員端：** 依指定日期查看全館教練課表及預約狀態。
- **後端驗證：** 檢查登入身分、會員購課資格、剩餘堂數、教練與時段限制，避免無效或重複預約。

我負責的部分主要涉及 **Controller → Service → Repository** 分層、DTO 資料傳遞、SQL Server 資料查詢，以及 React 與 Spring Boot API 串接。其他會員、出席與續約等模組為團隊分工成果。

**[查看 GitHub 專案](https://github.com/kikiwu853/GymProject)** ｜ [預約核心程式碼](https://github.com/kikiwu853/GymProject/blob/main/src/main/java/tw/gymproject/service/BookingService.java) ｜ [測試與驗證紀錄](https://github.com/kikiwu853/GymProject/blob/main/docs/PORTFOLIO_VALIDATION.md)

### 02｜永樂街鱔魚麵｜店家介紹網站

**專案類型：** 個人前端作品  
**技術：** HTML5、CSS3、JavaScript、Bootstrap 5

以家人經營的餐飲店為主題，製作可供訪客瀏覽的多頁式響應式網站：

- 使用 Bootstrap **Navbar、Grid、Carousel、Modal** 設計導覽與互動介面。
- 整合店家介紹、分類菜單、料理圖片及 Google Maps 地圖。
- 以 JavaScript 實作**美食扭蛋機**，隨機推薦餐點、動態計算總價並顯示結果。
- 製作聯絡表單的前端驗證與提示；目前**不含實際寄信功能**。

**[實際操作網站](https://kikiwu853.github.io/restaurant/)** ｜ [查看 GitHub 程式碼](https://github.com/kikiwu853/restaurant)

## 技術實作亮點

- **需求轉換成系統規則：** 將會員購課、預約、改期與取消需求轉為可驗證的後端流程。
- **前後端與資料庫串接：** 整合 React 操作畫面、Spring Boot API 與 SQL Server，處理資料關聯與回應格式。
- **使用者介面互動：** 以 Bootstrap 與原生 JavaScript 完成響應式排版、隨機推薦和 Modal 動態呈現。
- **Git 協作與專案整理：** 使用 Git 分支協作，整理 README、原始碼及作品展示連結。

## 作品連結

| 內容 | 連結 |
| --- | --- |
| 個人作品集首頁 | [Portfolio Website](https://kikiwu853.github.io/portfolio/) |
| Gym CRM 健身房管理系統 | [GitHub Repository](https://github.com/kikiwu853/GymProject) |
| 永樂街鱔魚麵線上網站 | [Live Demo](https://kikiwu853.github.io/restaurant/) |
| 永樂街鱔魚麵原始碼 | [GitHub Repository](https://github.com/kikiwu853/restaurant) |
