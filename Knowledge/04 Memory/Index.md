---
tags: [内存管理]
---
# 🧠 内存分配与管理
关注 glibc malloc、jemalloc、tcmalloc、mimalloc 等分配器的原理，以及碎片、RSS、Purge 等概念。
**子文件夹说明**：
- [[04 Memory/jemalloc|jemalloc]] – Redis/Valkey 默认分配器
- [[04 Memory/glibc malloc|glibc malloc]] – ptmalloc 原理
- 其他概念卡：Arena、Bin、Extent、Decay、Dirty Page、Fragmentation、RSS 等均以单独笔记存放，直接在下方列表显示
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/04 Memory"
WHERE file.name != "Index"
SORT file.name ASC