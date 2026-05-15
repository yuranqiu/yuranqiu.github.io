---
icon: fas fa-folder-open
order: 2
---

## 项目展示

### 资产探测系统

**核心开发者** | 2025/06 - 2025/08

针对大规模 URL 探测场景下的稳定性挑战，设计基于流式并发的系统架构，实现单节点日均稳定处理 **1500+ URL**。集成 Wappalyzer 指纹识别库与动态 JS 渲染引擎，自动化识别目标 Web 服务技术栈。封装基于 Docker Compose 的一键式部署方案，支持服务横向扩展。

**技术栈**：Python, FastAPI, Httpx, Wappalyzer, CDP, Docker

---

### 网站指纹识别多智能体系统

**核心开发者** | 2025/09 - 至今

构建"识别 → 校验 → 回流"工程闭环。指纹识别 Agent 利用 LangChain LCEL 设计多路 Skill 并行识别链路，在复杂 Banner 场景下将识别精度提升至 **95%+**。聚类分析 Agent 引入 TF-IDF + HDBSCAN 降低人工维护成本。指纹校验 Agent 利用小型 Embedding 模型构建双重校验，提升指纹质量稳定性。**覆盖率由 45.97% 提升至 95.97%**。

**技术栈**：Python, FastAPI, LangChain LCEL, HDBSCAN, TF-IDF, Elasticsearch