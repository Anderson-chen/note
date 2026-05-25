# [略]
全端工程師 | 5 年

---

## 關於我

全端工程師，主要使用 Java / Spring Boot（後端）與 Vue.js（前端），
在金融保險產業累積近 5 年開發經驗。
習慣進入陌生系統後先閱讀既有程式與業務邏輯，
理解脈絡後再規劃改動方向。

- 善於使用AI開發與驗證，做出決策前也能夠多方問答與查證
- 會積極了解不熟悉的業務與程式架構
- 喜歡推測與解決程式問題
- 樂於在新的情境上找到解決問題的方法


---

## 技術能力

**熟悉**：Java、TypeScript、Spring Boot、Spring Security、
Vue.js、Nuxt.js、Hexagonal Architecture、DDD、
OAuth2 / OIDC / JWT / PKCE、RESTful API / OpenAPI

**有使用過**：Spring Modulith、Spring Authorization Server、
Apache Kafka、Event-Driven Architecture、BFF

**資料庫**：Oracle、MSSQL、PostgreSQL、Redis

**工具與環境**：Docker、Jenkins、CI/CD、Flyway、
Quartz Scheduler、MapStruct、Gradle、Git、
JUnit（Unit + Integration Testing）

**雲端**：AWS EC2、S3

**AI 工具**：GitHub Copilot、Claude Code、Ollama、
Prompt Engineering、LLM Integration

---

## 工作經歷

### 緯創軟體 — 軟體工程師
2025/07 — 至今

**外溢保單現代化**
配合核心系統從 AS400 遷移至 Java 平台，負責 Java 端功能開發與流程整合。

- 負責外溢主檔同步、折扣計算開發，並參與部分折扣證明作業與通知單產製流程
- 開發前與 SA 協調實作內容（API 規格、DB 命名、程式風格），減少與原專案(Java平台)的差異性
- 整測階段與 AS400 核心系統使用 queue 串接，撰寫明確的規格與說明，並實作本地接收方法以加速整測時程
- 為複雜的流程建立多情境測試，並建立 mock server 模擬尚未就緒的外部系統（防火牆、未完成系統、特殊情境資料），使開發不受串接進度影響

*使用技術：Java 8、Spring MVC*

---

**AML 審查系統升級**
前期負責獨立升級 Vue 專案，後期支援 Spring Boot 升級與前後端串接驗證

- 將單一登入介接流程從公司客製 starter 遷至 Spring Security 原生實作，解決 starter 已不再維護問題
- 將 Vue 全面改寫為 Composition API，淘汰舊版為了寫法簡潔而引入、但 Vue 3 已不再支援的第三方 plugins，降低長期維護負擔
- 升級前以 Cypress E2E 補齊主流程與特殊案件的測試覆蓋，作為升級後行為一致性的驗證

*使用技術：Spring Boot 2 → Spring Boot 3、Vue 2 → Vue 3*

---

### 普鴻資訊 — 軟體工程師
2023/07 — 2025/02

**保單網路服務中心**
在已上線之保戶線上服務系統中，負責新功能的全端開發，並解決線上法規與資安問題

- 開發保戶端操作介面（保單查詢、契約異動等功能頁面）
- 與保單核心系統對接，實作保戶查詢、契約異動的後端服務，並將核心端資料轉換為保戶可讀的呈現格式
- 解決多項 Checkmarx 提出之弱點，使上線功能能提出完整的安全性報告
- 自行開發小工具，快速定位 log 中需遮罩的敏感欄位並反覆驗證

*使用技術：Spring Boot 2、Vue 2*

---

**電訪系統中台**
全新中台系統的全端開發，並負責後續優化與維運

- 從後端服務到前端介面，完整開發案件匯入、自動派案邏輯與問卷管理等核心功能
- 開發階段發現原派案策略規劃的盲點，主動提出解法並於程式中實作補強，補上規格未涵蓋的情境
- 將使用者提出的特殊情境整理為明確規則後實作，使系統能正確處理規格外的例外案件
- 主動處理使用者回饋的操作體驗問題（如問卷題目拖拉排序卡頓、題目不易閱讀），與使用者確認後調整前端介面
  
*使用技術：Spring Boot 3、Vue 3*

---

### 聯邦網通 — 軟體工程師
2021/06 — 2023/05

**銀行代收系統**
翻新 .NET 既有系統，並配合新需求進行全端開發

- 在無任何文件可參考下，透過需求訪談、觀察操作並交叉比對舊系統程式碼釐清現行功能，據以進行全端重寫
- 處理百萬筆等級歷史資料遷移，加入索引與客製邏輯避免查詢掃到舊資料，並驗證遷移後資料完整性
- 開發共用的 Excel 報表產製模組（Apache POI），讓組員免於重複實作報表產出邏輯，加速團隊開發
- 建立 Vue 共用元件，統一團隊樣式與寫法，降低 UI 不一致與重複程式碼
- 上線後主責專案開發進度與維運，並負責新進同仁的技術指導

*使用技術：Spring Boot、Vue 3*

---

## 學歷

[略]
