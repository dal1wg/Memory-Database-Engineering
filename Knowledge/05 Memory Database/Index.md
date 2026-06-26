---
tags: [内存数据库]
---
# ⚡ 内存数据库
对比和研究主流内存数据库及持久化 KV 引擎，重点是 Redis 和 Valkey。
**子文件夹说明**：
- [[05 Memory Database/Redis|Redis]] – 单机、持久化、事件循环等
- [[05 Memory Database/Valkey|Valkey]] – Redis 的社区分支，多线程 IO 等
- [[05 Memory Database/KeyDB|KeyDB]] – 多线程版本
- [[05 Memory Database/Dragonfly|Dragonfly]] – 现代内存存储
- [[05 Memory Database/Garnet|Garnet]] – 微软的远程缓存
- [[05 Memory Database/Kvrocks|Kvrocks]] – 基于 RocksDB
- [[05 Memory Database/Pika|Pika]] – 类 Redis 的磁盘 KV
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/05 Memory Database"
WHERE file.name != "Index"
SORT file.name ASC