# Hi, I'm itzk-sgh

**机器学习平台 · 大规模训练与推理**

2014 年起，我一直在做分布式系统与大规模计算相关的工作。目前在机器人公司的机器学习平台，负责算力调度、大规模训练加速以及在线推理加速。希望未来能用这些技术探索更多 AI 产品，服务社会、改善生活。

兴趣是写代码、登山，偶尔研究一点哲学。

---

## 走过的路

**2014 – 2016**  
参与离线分布式引擎 SKYNET。

**2016 – 2019**  
负责运营监控平台 Argus 与 DevOps 平台，完成私有化一键交付，并逐步进入云原生。当时手工落地 Kubernetes 的门槛还很高。

**2019 – 2022**  
转向机器学习平台，落地多机多卡训练、AutoML、训练加速，以及批任务与流水线调度。

**2022 – 2025**  
进入软硬结合行业，继续深耕机器学习平台：补齐日志与监控、网关、实验跟踪、数据集与模型版本管理，打通仿真与真机，形成从训练到部署的完整闭环。同期参与数据闭环，以及数仓与 BI 相关的数据工程。

**2025 – 至今**  
在机器人公司负责机器学习平台的算力工程，核心是调度、大规模训练与加速、在线推理与加速。目标是让「数据 → 仿真 → 真机」的闭环可交付、可运维。产品设计、架构、编码与交付运维，都尽量用 AI 贯穿。高频使用 Codex、Cursor、CodeBuddy、DeepSeek、Grok 等编码助手，具备丰富的 AI 辅助开发实战经验。

训练时，关注一次 step 的时间是耗在读数据、通信，还是卡没被喂饱；推理时，关注一次请求的时间是耗在调度、KV Cache、算子，还是模型精度与目标硬件不匹配。GPU 调度是这两件事的入口：设备插件决定卡以什么资源出现、隔离到什么程度；调度器决定 Pod 落在哪台机器、多机作业是否整组启动；队列决定谁先拿到卡，以及借出去的卡能否及时收回。

接下来会继续用 AI 探索各种产品，希望技术能真正服务社会、改善生活。

---

## 技术地图

按我接下来愿意投入的程度排序。

### 正在深挖

- **GPU 调度**：k8s-device-plugin、HAMi、Volcano、队列与抢占
- **推理与训练**：vLLM、分布式训练与推理链路、训推加速
- **实验与版本**：MLflow、TensorBoard、DVC、Notebook/JuptyLab

### 交付与运行

- **容器与编排**：Docker、Kubernetes、Knative
- **CI/CD 与发布**：Argo Workflow、Argo CD、Jenkins、GitLab
- **制品与通信**：Harbor、Nexus、gRPC

### 数据与任务

- **存储**：PostgreSQL、MySQL、SelectDB、MongoDB、Redis
- **流与调度**：Kafka、Flink、DolphinScheduler

### 观测与入口

- **监控与日志**：Prometheus、VictoriaMetrics、Grafana、Loki、ELK
- **网关与代理**：Kong、Higress、Nginx、Envoy

### AI工程

聚焦 AI 范式演进与工程化落地，深入研究 MCP、CLI、Agent/智能体、Skill 等关键方向，探索人机协作与 AI 高效利用的最佳实践。

---

## 联系

- **GitHub**：[itzk-sgh](https://github.com/itzk-sgh)
- **Email**：[1432353789@qq.com](mailto:1432353789@qq.com)

---

## GitHub 统计

![itzk-sgh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=itzk-sgh&show_icons=true&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=itzk-sgh&layout=compact)
