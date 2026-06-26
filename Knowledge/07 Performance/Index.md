---
tags: [性能工程]
---
# 📈 性能工程
性能分析方法、工具、基准测试规范，以及 CPU、内存、网络等维度的优化。
**子文件夹说明**：
- [[07 Performance/CPU|CPU 性能]] – 缓存、分支预测、CPI
- [[07 Performance/perf|perf 工具]] – perf record/stat/top 用法
- [[07 Performance/eBPF|eBPF]] – bpftrace、bcc 动态追踪
- [[07 Performance/FlameGraph|火焰图]] – 生成与解读
- [[07 Performance/Benchmark|基准测试]] – memtier、redis-benchmark 方法
- [[07 Performance/NUMA|NUMA 亲和]] – NUMA 对 Redis 的影响
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/07 Performance"
WHERE file.name != "Index"
SORT file.name ASC