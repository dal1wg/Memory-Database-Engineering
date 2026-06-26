---
tags: [Linux]
---
# 🐧 Linux 内核与系统
深入 Linux 内核中与内存数据库密切相关的子系统：内存管理、网络、进程等。
**子文件夹说明**：
- [[02 Linux/Memory/Index|内存]] – VMA、伙伴系统、Slab、THP、页表、OOM 等
- [[02 Linux/Network/Index|网络]] – epoll、io_uring、Socket、TCP/UDP、零拷贝
- [[02 Linux/Process|进程]] – fork、COW、信号、cgroup
- [[02 Linux/Scheduler|调度器]] – CFS、CPU 隔离
- [[02 Linux/Signal|信号]] – 信号处理机制
- [[02 Linux/Thread|线程]] – 多线程模型、同步
- 其他：Dynamic Linker、ELF、Filesystem、IPC、Kernel Debug
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/02 Linux"
WHERE file.name != "Index"
SORT file.name ASC