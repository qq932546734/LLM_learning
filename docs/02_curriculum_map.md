# LLM 知识地图（分层拆分）

## Level 0: 诊断与基础校准

- Tokenization、Embedding、Attention、Transformer 关键机制
- 目标：确认你是否需要补“最小理论底座”

## Level 1: Prompt 与基础应用

- Prompt 设计模式、结构化输出、工具调用、函数调用
- 上下文管理、few-shot 策略、错误类型
- 产出：可复用 Prompt 模板与评估样例集

## Level 2: RAG 系统

- 索引、切分、召回、重排、生成
- 混合检索、查询重写、上下文压缩、引用可追溯
- 产出：一个可评测的 RAG baseline

## Level 3: Agent 与工作流

- ReAct、Plan-Execute、Tool Router、多 Agent 协作
- 失败恢复、状态管理、可观测性
- 产出：一个可执行任务的 Agent 工作流

## Level 4: 评估与对齐

- Offline/Online Eval、LLM-as-a-judge、人工标注策略
- 幻觉率、忠实度、覆盖率、任务成功率
- 产出：自动评测脚本 + 指标面板定义

## Level 5: 训练与微调

- SFT、DPO/偏好优化、LoRA/QLoRA、数据构建
- 训练成本、过拟合、分布偏移
- 产出：一个小规模微调实验报告

## Level 6: 推理优化与部署

- 推理延迟、吞吐、KV Cache、量化、批处理
- 服务化、灰度、回滚、成本控制
- 产出：可上线的最小服务架构

## Level 7: 安全与治理

- Prompt Injection、越权工具调用、数据泄露
- 版权/合规/隐私、审计与风控策略
- 产出：安全检查清单 + 防护方案

