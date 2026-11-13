<h1 align="center">victoryloser</h1>

<p align="center"><strong>让模型接上数据，让执行有迹可查。</strong></p>
<p align="center">AI 应用 · Agent 工作流 · 评测 · RAG</p>
<p align="center"><a href="#代表项目">代表项目</a> · <a href="#工程关注点">工程关注点</a> · <a href="https://github.com/victoryloser?tab=repositories">全部仓库</a> · <a href="https://github.com/victoryloser/victoryloser/blob/main/README.md">English</a></p>

我用 Python 构建连接业务数据、持续任务和文档知识的 AI 应用。关注从提出问题、执行操作，到检查结果的完整过程。

## 代表项目

围绕数据分析、任务执行、轨迹评测和文档处理，展示四个方向的工程实践。

<table>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/ecommerce-analysis-agent"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-analytics.svg" width="80" height="80" alt="经营数据分析 Agent" /></a></td>
<td valign="top">
<p><sub>01 / 数据分析</sub></p>
<h3><a href="https://github.com/victoryloser/ecommerce-analysis-agent">经营数据分析 Agent</a></h3>
<p>用自然语言提出经营问题，查看数据库计算结果，再下钻到具体明细。</p>
<p>自然语言问数 · 图表下钻 · 只读 SQL</p>
<p><code>Gradio</code> <code>DuckDB</code></p>
<p><a href="https://github.com/victoryloser/ecommerce-analysis-agent/blob/main/README.zh-CN.md">中文文档</a> · <a href="https://github.com/victoryloser/ecommerce-analysis-agent/blob/main/docs/data-format.md">数据格式</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/tax-task-agent"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-workflows.svg" width="80" height="80" alt="财税任务助手" /></a></td>
<td valign="top">
<p><sub>02 / 任务执行</sub></p>
<h3><a href="https://github.com/victoryloser/tax-task-agent">财税任务助手</a></h3>
<p>通过对话查询收支、保存发票用途与备注，以授权、查回和持续任务记录办理结果。</p>
<p>受控保存 · 持久队列 · 跨会话任务</p>
<p><code>Streamlit</code> <code>LangGraph</code> <code>SQLite</code></p>
<p><a href="https://github.com/victoryloser/tax-task-agent/blob/main/README.zh-CN.md">中文文档</a> · <a href="https://github.com/victoryloser/tax-task-agent/blob/main/docs/data-format.md">数据格式</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/invoice-trace-evaluator"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-evaluation.svg" width="80" height="80" alt="开票轨迹评测器" /></a></td>
<td valign="top">
<p><sub>03 / 轨迹评测</sub></p>
<h3><a href="https://github.com/victoryloser/invoice-trace-evaluator">开票轨迹评测器</a></h3>
<p>重建开票 Agent 的执行状态，定位首错与传播路径，依据事件证据比较两个版本。</p>
<p>时序状态 · 根因分析 · 交互时间线</p>
<p><code>Pydantic</code> <code>JSON Schema</code> <code>Jinja2</code></p>
<p><a href="https://github.com/victoryloser/invoice-trace-evaluator/blob/main/README.zh-CN.md">中文文档</a> · <a href="https://github.com/victoryloser/invoice-trace-evaluator/blob/main/docs/data-format.md">轨迹格式</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/medical-agent-platform"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-documents.svg" width="80" height="80" alt="医疗文档与 Agent 平台" /></a></td>
<td valign="top">
<p><sub>04 / 文档处理</sub></p>
<h3><a href="https://github.com/victoryloser/medical-agent-platform">医疗文档与 Agent 平台</a></h3>
<p>连接医疗文档处理、知识检索与异步任务，构建可人工复核的 Agent 工作流。</p>
<p>OCR 与脱敏 · 混合 RAG · 图谱检索</p>
<p><code>FastAPI</code> <code>Milvus</code> <code>Neo4j</code></p>
<p><a href="https://github.com/victoryloser/medical-agent-platform/blob/main/docs/README_zh-CN.md">中文文档</a> · <a href="https://github.com/victoryloser/medical-agent-platform/blob/main/docs/medical-architecture.md">架构说明</a></p>
</td>
</tr>
</table>

各项目文档包含支持的数据格式、启动方式和使用边界。

## 工程关注点

- **依据明确：** 让计算结果、检索来源和事件证据能够被检查。
- **过程可控：** 用显式状态、权限检查和持久化任务组织执行。
- **便于复现：** 提供数据接入说明、离线测试和可操作的启动步骤。

## 常用技术

| 方向 | 技术 |
|---|---|
| 应用与工作流 | `Python` · `FastAPI` · `LangGraph` · `Gradio` · `Streamlit` |
| 数据与检索 | `DuckDB` · `SQLite` · `PostgreSQL` · `Milvus` · `Neo4j` |
| 契约与评测 | `Pydantic` · `JSON Schema` · `pytest` |

## 更多项目

- [图像标注处理工具](https://github.com/victoryloser/process_data)：LabelMe 合并与筛选、分割 mask 生成和图像格式处理。
- [Agent Runtime Kit](https://github.com/victoryloser/agent-runtime-kit)：fork 自 [zed123214/kitagent](https://github.com/zed123214/kitagent)。

---

欢迎在对应项目中提交 Issue，讨论问题和改进建议。
