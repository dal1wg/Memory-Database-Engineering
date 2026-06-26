---
tags: [调试]
---
# 🐞 调试与剖析
代码级调试、内存错误检测、系统调用追踪等工具与案例。
**子文件夹说明**：
- [[08 Debug/GDB|GDB]] – 多进程/多线程调试 Redis
- [[08 Debug/strace|strace]] – 系统调用追踪
- [[08 Debug/Valgrind|Valgrind]] – 内存泄漏/越界
- [[08 Debug/ASan|ASan]] / [[08 Debug/TSan|TSan]] / [[08 Debug/UBSan|UBSan]] – 编译器消毒器
- [[08 Debug/Heaptrack|Heaptrack]] – 堆剖析
- [[08 Debug/rr|rr]] – 可逆调试
- [[08 Debug/Crash|Crash 分析]] – 核心转储、backtrace
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/08 Debug"
WHERE file.name != "Index"
SORT file.name ASC