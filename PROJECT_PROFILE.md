# 🕹️ 專案 02：獨立課堂遊戲大廳 (bio-standalone-games)

本檔案為 **大廳二（bio-standalone-games）** 之權威專案身分證與架構設定檔。

---

## 📌 專案基本資料

* **專案識別名稱**：`02_大廳二_獨立課堂遊戲大廳 (bio-standalone-games)`
* **本機唯一路徑**：`D:\AI Agent\教學專案系統\02_大廳二_獨立課堂遊戲大廳 (bio-standalone-games)`
* **GitHub 倉庫**：[`zeroseven-hue/bio-standalone-games`](https://github.com/zeroseven-hue/bio-standalone-games)
* **GitHub Pages 線上站點**：[https://zeroseven-hue.github.io/bio-standalone-games/](https://zeroseven-hue.github.io/bio-standalone-games/)
* **Git 主要分支**：`main`
* **架構核心**：**獨立專屬題庫與專屬倉庫（Self-Contained Repositories）**
  * 與大廳一最大的差別：此處收錄的遊戲**「不依賴」大廳一的中央共用題庫**！
  * 每一款遊戲都有自己專屬的 GitHub 倉庫、專屬的 36 題以上深度單元題庫與專屬主題規則。

---

## 🎮 大廳二精選收錄的 3 款獨立遊戲

| 編號 | 專案名稱 | 獨立 GitHub 倉庫 | 線上體驗網址 | 核心特色與專屬題庫 |
| :---: | :--- | :--- | :--- | :--- |
| 1 | 🫀 **《人體消化大冒險》** | [`bio-digestive-game`](https://github.com/zeroseven-hue/bio-digestive-game) | [即刻遊玩](https://zeroseven-hue.github.io/bio-digestive-game/) | 54 格消化系統大地圖、36 題專屬消化與酵素題庫、雙模運作 (線上Fetch + 離線備用題庫)。 |
| 2 | 🧋 **《珍珠奶茶大對決》** | [`boba-reaction-game`](https://github.com/zeroseven-hue/boba-reaction-game) | [即刻遊玩](https://zeroseven-hue.github.io/boba-reaction-game/) | 毫秒級 (ms) 反應力 PK、大螢幕雙人對決、神經傳導與反射專屬題庫。 |
| 3 | 🔬 **《五界研究所：微觀視野探險記》** | [`bio-five-kingdoms-game`](https://github.com/zeroseven-hue/bio-five-kingdoms-game) | [即刻遊玩](https://zeroseven-hue.github.io/bio-five-kingdoms-game/) | 36 種珍稀生物分類特徵檢索表、圖鑑收集模式、原核/原生/真菌/植物/動物五界專屬題庫。 |

---

## ⚙️ 核心檔案架構

* `index.html`：大廳二主首頁，包含美觀的 3 大獨立遊戲展示卡片與專屬標籤。
* `games.json`：大廳二之卡片設定資料庫，載明各遊戲之標題、標籤、色彩、描述與 GitHub Pages 跳轉 URL。
* 頂部導覽列：具備「大廳一（主題遊戲）」、「大廳二（獨立遊戲）」、「大廳三（教學工具）」、「大廳四（導師神器）」的一鍵切換按鈕。

---

## 🚫 邊界鐵則（嚴禁越界）

1. **絕不混入中央題庫**：大廳二的定位是「專題深度體驗」，嚴禁將其改為依賴大廳一的 `questions/manifest.json`。
2. **新增遊戲標準**：若未來要加入大廳二，必須滿足「具備高度客製化主題規則（如反應時間、圖鑑、專屬地圖）且自帶題庫」之條件。
