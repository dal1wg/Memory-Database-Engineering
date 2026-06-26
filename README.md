# Memory Database Engineering

> Linux Kernel + Memory Database + Distributed System Engineering Knowledge Base

这是个人深入 Redis/Valkey 及 Linux 内核的工程化知识库，覆盖 **开发、运维、部署、架构设计** 全视角，以源码分析 + 系统层实验 + 可复现调试为核心方法。

## 📂 仓库结构
- `Knowledge/`：Obsidian 知识库本体（笔记、MOC、实验、案例）
- `Templates/`：Templater 动态模板（概念、实验、源码分析等）
- `Scripts/`：调试与分析辅助脚本（GDB 宏、perf 命令、bpftrace 脚本）
- `Benchmarks/`：原始压测数据与火焰图
- `Labs/`：实验环境配置与一次性测试代码
- `Books/`、`Papers/`、`References/`：外部参考资料及其笔记索引
- `Projects/`：独立工程模块（如手写 Redis 模块）

## 🚀 快速开始
1. 克隆仓库到本地
2. 用 Obsidian 打开 `Knowledge/` 作为 Vault
3. 确保已安装并启用以下插件：
   - Dataview
   - Templater
   - Excalidraw
   - Obsidian Git（用于版本控制）
4. 从 `Knowledge/00 Portal/Home` 开始浏览

## 🧭 学习路线
请查看 [[Knowledge/00 Portal/Roadmap]]，总体分为 5 个阶段：
1. Linux 内核基础（进程、内存、页表等）
2. 内存分配器（glibc malloc、jemalloc 深入）
3. Redis 内核（数据结构、事件循环、持久化、集群）
4. 性能工程（perf、eBPF、火焰图、缓存）
5. 工程实践（生产案例、优化、Patch）

## 📋 维护方式
- 用 `CHANGELOG.md` 记录知识库本身的重大更新。
- 所有笔记通过 Obsidian 内部链接组织，杜绝孤立卡片。
- 每周回顾 `Inbox` 并清理 `TODO`。

## 📄 许可
本仓库为个人学习用途，部分代码脚本可能来自社区示例，请遵循其原始许可证。