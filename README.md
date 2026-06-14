# learn-the-deep

> 一邊讀書、一邊記錄的學習筆記 repo。深入底層、把觀念畫成圖。

目前主線：閱讀《**架構師的自我修煉**》，搭配電腦網路、系統設計等底層主題的延伸筆記。

## 📚 目前進度

- 📖 正在讀：《架構師的自我修煉》 → [讀書筆記](./books/架構師的自我修煉/)

## 🗂️ 檔案結構

依主題分類歸檔，每個分類資料夾內有自己的 README 索引。

```
learn-the-deep/
├── README.md                ← 你在這
├── networking/              🌐 網路底層
│   └── osi-tcp-http.md
├── system-design/          🏗️ 系統設計 / 架構
│   └── load-balancing-dr-mac-rewrite.md
├── storage/                💾 儲存（硬碟 / 檔案系統 / RAID / 分散式）
│   └── disk-filesystem-raid-hdfs.md
├── operating-system/       🖥️ 作業系統（規劃中）
├── database/               🗄️ 資料庫（規劃中）
└── books/                  📖 讀書筆記
    └── 架構師的自我修煉/
```

## 📑 筆記索引

| 分類 | 筆記 | 內容 |
|------|------|------|
| [🌐 networking](./networking/) | [osi-tcp-http.md](./networking/osi-tcp-http.md) | OSI 七層 × TCP × HTTP 學習圖、封裝鏈路、HTTPS 時序、心智圖、`curl -v` 抓包對照 |
| [🏗️ system-design](./system-design/) | [load-balancing-dr-mac-rewrite.md](./system-design/load-balancing-dr-mac-rewrite.md) | 從一次搜尋出發：L4/L7 負載平衡、LVS 三模式、Direct Routing 改寫 MAC、DSR 效益、Anycast/Maglev/Service Mesh、對前端的影響 |
| [💾 storage](./storage/) | [disk-filesystem-raid-hdfs.md](./storage/disk-filesystem-raid-hdfs.md) | HDD/SSD 原理、檔案系統與 inode、為何單機難處理 100TB 大檔、RAID 0/1/10/5/6、分散式檔案系統 HDFS（NameNode/DataNode/副本） |

## 🎯 這個 repo 在做什麼

- 把讀到的觀念整理成**可視化筆記**（大量使用 Mermaid 圖：流程圖、時序圖、心智圖）
- 從「整體鏈路」到「關聯心智圖」，建立主題之間的連結
- 依主題歸檔，邊讀邊記、持續累積

## 🔧 渲染說明

筆記內的圖使用 [Mermaid](https://mermaid.js.org/)，在 GitHub、VS Code（裝 Mermaid 外掛）、Obsidian 等皆可直接渲染。

> Mermaid `mindmap` 的節點文字避免使用括號 `()` 與 `::icon`，否則 GitHub 會 parse error。

---

_持續更新中 ✍️_
