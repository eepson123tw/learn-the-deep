# 🏗️ System Design 系統設計 / 架構

可擴展、高可用系統的架構觀念：負載平衡、快取、佇列、分散式。

## 筆記

| 筆記 | 內容 |
|------|------|
| [load-balancing-dr-mac-rewrite.md](./load-balancing-dr-mac-rewrite.md) | 從一次搜尋出發：L4/L7 負載平衡、LVS 三模式、Direct Routing 改寫 MAC、DSR 效益、Anycast/Maglev/Service Mesh 等做法、對前端的影響 |

## 規劃中（待補）

- 快取策略（Cache-Aside / Write-Through / CDN）
- 訊息佇列與非同步處理
- 資料分片 (Sharding) 與一致性雜湊
- CAP 理論與一致性模型
