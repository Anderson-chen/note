# 面試筆記

> T1 Java｜T2 Spring Boot｜T3 Vue 3｜T4 系統設計｜T5 DevOps｜T6 演算法

---

## T4 系統設計

**名詞**

| 名詞 | 說明 |
|---|---|
| 倒排索引 | 詞 → 文件列表，O(1) 查找，ES 全文檢索核心 |
| IK Analyzer | 中文切詞器，避免逐字切導致精準度低 |
| BM25 | ES 排名演算法，優於 PostgreSQL ts_rank |
| Shard / Replica | 分片（水平擴展）/ 備份（高可用）|
| 雙寫問題 | 同時寫兩個 DB，其中一個失敗造成不一致 |
| CDC / Debezium | 監聽 binlog 自動同步，解決雙寫問題 |
| 最終一致性 | 資料最終會同步，但有短暫延遲 |
| ACID | 原子性、一致性、隔離性、持久性 |
| MVCC | PostgreSQL 並發控制，讀不阻擋寫 |

**重點**

- `LIKE '%keyword%'` 全表掃描，500 萬筆必須用 ES
- 中文搜尋一定裝 IK Analyzer
- 庫存 / 金融餘額需強一致性 → 不放 ES，即時查 PostgreSQL
- 新專案選 PostgreSQL，MySQL 適合 LAMP / 讀多簡單查詢

---

## T1 Java Core

<!-- 待補 -->

---

## T2 Spring Boot 3

<!-- 待補 -->

---

## T3 Vue 3

<!-- 待補 -->

---

## T5 DevOps

<!-- 待補 -->

---

## T6 演算法

<!-- 待補 -->
