# Level 0 诊断测评（首次能力基线）

## Part A: 概念快问（口头/文字）

1. 解释 `temperature`、`top_p`、`max_tokens` 的差异和联动。
2. RAG 中“召回差”与“生成差”如何区分定位？
3. 为什么“高分 embedding”不等于“高质量回答”？
4. 你如何定义“幻觉”？如何量化？
5. 函数调用与 Agent 的边界是什么？

## Part B: 实战任务（60-90 分钟）

- 任务：实现一个最小 RAG pipeline（索引 + 检索 + 生成）
- 要求：
  - 返回答案时附带引用片段
  - 输出至少 3 条失败样例及原因
  - 给出 2 个可执行优化点

## Part C: 设计题（20 分钟）

- 场景：预算固定，每天 1 万请求，如何平衡效果、延迟、成本？
- 输出：架构草图 + 指标 + 监控项 + 回滚策略

## 评分

- 按 [04_assessment_framework.md](/Users/didi/work/LLM_learning/docs/04_assessment_framework.md) 四维打分
- 诊断结果写入 [05_progress_tracker.md](/Users/didi/work/LLM_learning/docs/05_progress_tracker.md)

