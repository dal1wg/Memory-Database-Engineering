---
tags: [云原生]
---
# ☁️ 云原生与部署
Redis/Valkey 在容器、K8s、Operator 模式下的部署、编排和运维。
**子文件夹说明**：
- [[09 Cloud/Docker|Docker]] – Dockerfile、compose 编排 Redis
- [[09 Cloud/Kubernetes|Kubernetes]] – StatefulSet、ConfigMap
- [[09 Cloud/Helm|Helm]] – Redis/Valkey 的 Helm Chart
- [[09 Cloud/Operator|Operator]] – Redis Operator 工作原理
## 📋 本层笔记
```dataview
LIST
FROM "Memory-Database-Engineering/Knowledge/09 Cloud"
WHERE file.name != "Index"
SORT file.name ASC