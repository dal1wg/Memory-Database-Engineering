---
tags: [实验]
---
# 🧪 实验记录
所有可复现的调优、压测、故障注入实验，每个实验对应一篇笔记（使用 `Experiment` 模板）。
**无子文件夹**，所有实验笔记直接存放在此目录下，便于 Dataview 汇总。
## 📋 实验列表
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/10 Experiments"
WHERE file.name != "Index"
SORT file.ctime DESC