---
tags: [编程语言]
---
# 📝 编程语言与工具
掌握 Redis/Valkey 源码及性能工具所需的核心语言：C、C++、Go、Rust、汇编等。
**子文件夹说明**：
- [[03 Programming/Assembly|汇编]] – AT&T/Intel 语法，读懂反汇编
- [[03 Programming/C|C语言]] – 系统编程核心，Redis 主要语言
- [[03 Programming/C++|C++]] – 部分 Redis 模块、测试工具
- [[03 Programming/Go|Go]] – 云原生工具链、部分集群代理
- [[03 Programming/Rust|Rust]] – 新兴内存安全语言，部分存储引擎
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/03 Programming"
WHERE file.name != "Index"
SORT file.name ASC