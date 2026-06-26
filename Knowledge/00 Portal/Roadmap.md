---
tags: [门户, 路线图]
created: 2026-06-26
---

# Memory Database Engineering Roadmap

> 五大阶段，从 Linux 内核基础到工程实践。  
> 完成一项勾选一项，并新建对应概念笔记（如 `[[fork]]`、`[[SDS]]`）。

---

## Phase 1: Linux Foundation

### Process
- [ ] Process Model
- [ ] fork
- [ ] exec
- [ ] signal
- [ ] namespace

### Memory
- [ ] Virtual Memory
- [ ] Page Table
- [ ] Page Fault
- [ ] Buddy Allocator
- [ ] Slab
- [ ] mmap
- [ ] brk
- [ ] NUMA
- [ ] THP

---

## Phase 2: Memory Allocator

### malloc
- [ ] glibc malloc

### jemalloc
- [ ] Arena
- [ ] Bin
- [ ] Extent
- [ ] Tcache
- [ ] Decay
- [ ] Fragmentation

---

## Phase 3: Redis Kernel

### Data Structure
- [ ] SDS
- [ ] Dict
- [ ] Listpack
- [ ] Quicklist
- [ ] Skiplist

### Core
- [ ] Event Loop
- [ ] Persistence
- [ ] Replication
- [ ] Cluster

---

## Phase 4: Performance

- [ ] perf
- [ ] eBPF
- [ ] FlameGraph
- [ ] CPU Cache
- [ ] NUMA

---

## Phase 5: Engineering

- [ ] Production Case
- [ ] Optimization
- [ ] Patch

---

## 使用建议
- 每个概念完成后，创建一个笔记（如 `[[fork]]`），并链接到对应的 MOC 或实验。
- 可在每条待办后添加 `#todo` 标签，方便 Dataview 查询所有待学概念。