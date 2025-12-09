<p align="right">
  <a href="README.md">English</a> | 繁體中文
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=js051&theme=react-dark" alt="GitHub 活動圖" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=js051&theme=github_dark" alt="個人概要" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=js051&theme=github_dark" alt="統計資料" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=js051&theme=github_dark" alt="主要程式語言" />
</p>

---

# js051

Full-stack Industrial Systems / Embedded / Python

主要關注工業系統、冷卻控制（CDU 類型系統）、嵌入式韌體與後端整合。  
日常工作多半是把 MCU / PLC 控制邏輯、Python 後端服務、Web 介面，以及實際現場需要的部署與更新流程串成一套可維護的系統。

---

## 關於我

- 來自台灣，背景是資訊工程（Computer Science and Information Engineering）  
- 大學畢業專題：使用遺傳演算法（Genetic Algorithm）實作排課系統  
- 目前主要負責工業相關專案：冷卻系統、測試系統、控制平台等  
- 習慣從底層到上層都自己摸過一遍：
  - STM32 等 MCU 韌體開發、通訊協定（例如 Modbus RTU）
  - Python / Flask 服務、類 Redfish 介面、基本 Web UI
  - Linux 環境建置、離網部署、Shell Script 自動化與更新流程設計  

公司相關專案與程式碼多為私有或放在內部 Git 伺服器，因此 GitHub 上主要是個人練習、Side Project 與實驗性質的程式碼。

---

## 技術與工具 Tech Stack

### 語言 Languages

- C / C++（嵌入式開發、MCU 韌體）
- Python（Flask、腳本、工具程式）
- JavaScript / TypeScript（主要在 Next.js / React）
- LabVIEW（測試自動化、ATE 流程）

### 嵌入式與控制 Embedded & Control

- STM32 系列 MCU：UART、ADC、PWM、Timer、GPIO 等周邊  
- 通訊：Modbus RTU、RS-485、一般串列通訊  
- I/O 與工業現場經驗：DI/DO、風扇控制、感測器讀取、安全保護邏輯  

### 後端與系統 Backend / System

- Python + Flask：用於 API、Web UI、控制面板
- Linux / Ubuntu Server、systemd services、基本 Nginx 配置
- Shell Script 自動化、離線安裝包（wheelhouse、離線 apt 套件庫）
- 基本 Docker 使用經驗與 CI/CD 流程設計（以 GitHub Actions 為主）

### 前端 Frontend

- Next.js（React）+ Tailwind CSS
- Flask + Bootstrap 5
- 介面風格以「工具型系統儀表板」為主，強調可讀性與實用性，而不是純視覺效果

---

## 代表作品 Selected Projects

### Timetabling Problem with Genetic Algorithm

大學畢業專題，使用遺傳演算法產生課表。

- 對課程、教師、教室、時段等約束進行建模  
- 實作遺傳演算法的選擇（Selection）、交配（Crossover）、突變（Mutation）流程  
- 透過 Web 介面將產生的課表視覺化呈現  

連結：

- Demo：<https://gene.dong3.me/chromosome>  
- Source：<https://github.com/dddong3/timetabling_problem>

---

### guzzzi.com

個人 Side Project 與全端練功場，用來實驗與整合各種想法。

- 網站：<https://guzzzi.com/>  
- 使用 Next.js 與 Tailwind CSS，部分功能整合 Firebase  
- 計畫持續擴充：
  - 技術文章與筆記整理
  - 各種小工具（查詢工具、練習用 API、實用性功能等）

---

### 工業與私人專案（概念性描述）

多數專案放在公司內部 Git 或私有儲存庫，無法公開程式碼，以下僅做大略敘述：

- 工業冷卻系統控制（CDU 類型系統）  
- 以 STM32 為主的 MCU 韌體：包含 Modbus RTU 通訊、ADC 量測、PWM 控制、數位 I/O  
- Python 後端服務與 Web 介面，用於設備監控、參數設定、韌體更新  
- 離網環境部署與更新機制設計：離線安裝包、自動化腳本、遠端更新與回滾策略

---

## 目前關注主題 What I Am Focusing On

- 設計可重用、可靠的 MCU Bootloader 與韌體更新架構  
- 為工業現場建立穩定的部署流程，包括 rollback、offline update 等考量  
- 更系統性地整理與抽象 Python / Flask / 類 Redfish 的後端架構  
- 逐步補強深度學習與資料分析基礎，未來導入到工業設備的監控與異常偵測  

---

## 聯絡與合作 Contact

如果你對以下主題有興趣，歡迎交流：

- 工業控制系統、冷卻相關系統  
- MCU / 嵌入式韌體、Modbus RTU  
- Python 後端、類 Redfish API、Web 介面與離網部署  

目前建議的聯絡方式：

- 在本帳號的公開 Repo 開 GitHub Issues / 使用 Discussions  
- 或透過我的個人網站（以及未來會補上的聯絡方式）：<https://guzzzi.com/>
