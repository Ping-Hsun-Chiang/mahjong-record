# 🀄 麻將紀錄 Mahjong Record

一個以 **個人麻將損益追蹤** 為核心的輕量化網頁工具，目標是讓玩家能夠快速記錄每一把的輸贏結果，並透過視覺化圖表掌握自己的長期走勢。無需安裝、無需登入，開啟即用。

## Website
- Live Site: [https://ping-hsun-chiang.github.io/mahjong-record/](https://ping-hsun-chiang.github.io/mahjong-record/)

## Project Overview
本專案以單一 HTML 檔案實作完整功能，結合本地儲存與互動式圖表，打造出一個方便日常使用的麻將記帳工具。除了基本的輸贏記錄外，亦加入了資料視覺化與資料匯出功能，讓每一把的結果都有跡可循：

- 快速新增每把輸贏紀錄，含日期、金額與備註
- 自動彙整本月、本年與累計損益總覽
- 視覺化走勢圖表，直觀呈現輸贏消長
- 支援 JSON 匯出 / 匯入，方便備份與跨裝置使用

這讓專案不只是單純的記帳清單，而是一個有完整資料管理流程的個人財務追蹤工具。

## Main Features

### 1. 損益總覽儀表板
- 本月損益快速摘要
- 本年累計損益彙整
- 歷史累計損益一覽

### 2. 紀錄新增與管理
- **新增紀錄**：選擇日期、贏／輸、金額，可附加備註
- **紀錄列表**：依時間序瀏覽所有歷史紀錄
- **統計摘要**：自動計算場數、勝率、平均損益等統計數據

### 3. 視覺化圖表
- **累計損益走勢圖**：以折線圖呈現每把累積後的損益變化
- **月結圖**：以柱狀圖彙整各月份的整體輸贏表現
- 支援前後月份切換瀏覽

### 4. 資料管理
- **匯出 JSON**：將所有紀錄匯出為本地 JSON 檔案，方便備份
- **匯入 JSON**：從備份檔案還原紀錄，支援跨裝置使用
- **清除全部**：一鍵重置，清空所有紀錄

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- **LocalStorage**（瀏覽器本地資料儲存）
- **Canvas API / Chart.js**（圖表視覺化）
- **Responsive Web Design (RWD)**
- **GitHub Pages**

## Author
**Ping-Hsun Chiang**  
GitHub: [Ping-Hsun-Chiang](https://github.com/Ping-Hsun-Chiang)
