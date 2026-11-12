<div align="center">

<img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/profile-banner.svg" alt="victoryloser：AI 应用、Agent 与检索系统" width="100%" />

**围绕文档、知识和经营数据，构建能实际使用的 AI 应用。**

[代表项目](#代表项目) · [工程关注点](#工程关注点) · [全部仓库](https://github.com/victoryloser?tab=repositories) · [English](https://github.com/victoryloser/victoryloser/blob/main/README.md)

</div>

## 我在做什么

这些项目围绕模型能力的实际落地展开：接入合适的上下文，明确工作流，并让结果可以检查。

- **Agent 工作流：** 结构化规划、工具执行、会话状态和人工复核。
- **检索与文档：** 混合检索、重排、医疗文档处理和带来源依据的回答。
- **经营与数据工具：** 自然语言问数、只读 SQL 和图像标注处理。

## 代表项目

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/victoryloser/ecommerce-analysis-agent">经营数据分析 Agent</a></h3>
<p>用自然语言提出经营问题，查看数据库计算的结果，并从分组继续查看明细。</p>
<p>自然语言问数 · 图表下钻 · 持久会话 · 只读 SQL</p>
<p><code>Python</code> <code>Gradio</code> <code>DuckDB</code></p>
<p><a href="https://github.com/victoryloser/ecommerce-analysis-agent/blob/main/README.zh-CN.md">中文文档</a> · <a href="https://github.com/victoryloser/ecommerce-analysis-agent/blob/main/docs/data-format.md">数据格式</a></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/victoryloser/medical-agent-platform">医疗文档与 Agent 平台</a></h3>
<p>将医疗文档处理与检索、异步任务和可复核的 Agent 工作流连接起来。</p>
<p>OCR 与脱敏 · 混合 RAG · 图谱检索 · 人工复核</p>
<p><code>FastAPI</code> <code>LangGraph</code> <code>Milvus</code> <code>Neo4j</code></p>
<p><a href="https://github.com/victoryloser/medical-agent-platform#quick-start">快速开始</a> · <a href="https://github.com/victoryloser/medical-agent-platform/blob/main/docs/medical-architecture.md">医疗架构</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/victoryloser/medical-consultation-agent">多模态医疗辅助问诊</a></h3>
<p>探索图文输入下的辅助问诊流程，包含急症分流、知识检索和明确的安全检查。</p>
<p>多模态输入 · 条件路由 · 依据核查 · 本地/API 模型</p>
<p><code>FastAPI</code> <code>LangGraph</code> <code>Gradio</code> <code>ChromaDB</code></p>
<p><a href="https://github.com/victoryloser/medical-consultation-agent#quick-start">快速开始</a> · <a href="https://github.com/victoryloser/medical-consultation-agent/blob/main/README.zh-CN.md">中文文档</a></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/victoryloser/law_Rag">劳动法 RAG</a></h3>
<p>围绕中文劳动法问答，探索混合检索、重排、查询改写和效果评估。</p>
<p>BM25 + 向量检索 · RRF · HyDE · 流式 API</p>
<p><code>LlamaIndex</code> <code>ChromaDB</code> <code>FastAPI</code> <code>QLoRA</code></p>
<p><a href="https://github.com/victoryloser/law_Rag#quick-start">快速开始</a> · <a href="https://github.com/victoryloser/law_Rag/blob/master/README.zh-CN.md">中文文档</a></p>
</td>
</tr>
</table>

医疗和法律项目用于学习与工程探索，具体使用边界和评估条件见各项目文档。

## 工程关注点

| 方向 | 关注内容 |
|---|---|
| 上下文与检索 | 来源引用、混合检索、重排和查询优化 |
| 工作流控制 | 显式状态、条件分支、有界执行，以及必要时的人工复核 |
| 结果可检查 | 计算口径、执行轨迹、评估脚本和查询记录 |
| 使用体验 | API、Gradio 界面、数据导入流程和可操作的启动说明 |

**常用技术：** `Python` · `FastAPI` · `LangGraph` · `LlamaIndex` · `Gradio` · `DuckDB` · `ChromaDB` · `Milvus` · `Neo4j`

## 更多项目

- [图像标注处理工具](https://github.com/victoryloser/process_data)：LabelMe 合并与筛选、分割 mask 生成、图像模式检查和灰度转换。
- [Agent Runtime Kit](https://github.com/victoryloser/agent-runtime-kit)：[zed123214/kitagent](https://github.com/zed123214/kitagent) 的 **fork**，单独标注其来源。

有问题或建议，可以在对应项目中提交 Issue。
