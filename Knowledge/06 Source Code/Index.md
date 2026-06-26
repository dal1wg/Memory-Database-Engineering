---
tags: [源码分析]
---
# 🔬 源码分析
逐文件、逐函数分析 Redis、Valkey、jemalloc 和 Linux 内核关键代码。
**子文件夹说明**：
- [[06 Source Code/Redis|Redis 源码]] – 版本 x.x，含注释笔记
- [[06 Source Code/Valkey|Valkey 源码]] – 与 Redis 差异对比
- [[06 Source Code/jemalloc|jemalloc 源码]] – 分配器内部实现
- [[06 Source Code/Linux|Linux 内核源码]] – 与 Redis 相关的子系统
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/06 Source Code"
WHERE file.name != "Index"
SORT file.name ASC