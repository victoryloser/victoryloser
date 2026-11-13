<h1 align="center">victoryloser</h1>

<p align="center"><strong>Connect models to data. Keep the work inspectable.</strong></p>
<p align="center">AI applications · Agent workflows · Evaluation · RAG</p>
<p align="center"><a href="#selected-work">Selected work</a> · <a href="#engineering-focus">Engineering focus</a> · <a href="https://github.com/victoryloser?tab=repositories">All repositories</a> · <a href="https://github.com/victoryloser/victoryloser/blob/main/README.zh-CN.md">简体中文</a></p>

I build Python applications that connect models with business data, persistent workflows, and document knowledge. My focus is the path from asking a question to executing a task and checking the result.

## Selected work

Four projects across analysis, execution, evaluation, and document intelligence.

<table>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/ecommerce-analysis-agent"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-analytics.svg" width="80" height="80" alt="Ecommerce Analysis Agent" /></a></td>
<td valign="top">
<p><sub>01 / ANALYTICS</sub></p>
<h3><a href="https://github.com/victoryloser/ecommerce-analysis-agent">Ecommerce Analysis Agent</a></h3>
<p>Ask business questions, inspect database calculations, and drill into results.</p>
<p>Natural-language queries · Chart drilldowns · Read-only SQL</p>
<p><code>Gradio</code> <code>DuckDB</code></p>
<p><a href="https://github.com/victoryloser/ecommerce-analysis-agent#readme">Documentation</a> · <a href="https://github.com/victoryloser/ecommerce-analysis-agent/blob/main/docs/data-format.md">Data format</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/tax-task-agent"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-workflows.svg" width="80" height="80" alt="Tax Task Agent" /></a></td>
<td valign="top">
<p><sub>02 / WORKFLOWS</sub></p>
<h3><a href="https://github.com/victoryloser/tax-task-agent">Tax Task Agent</a></h3>
<p>Query finances and save invoice details with authorized edits, readback, and persistent tasks.</p>
<p>Controlled edits · Durable queue · Cross-session tasks</p>
<p><code>Streamlit</code> <code>LangGraph</code> <code>SQLite</code></p>
<p><a href="https://github.com/victoryloser/tax-task-agent#readme">Documentation</a> · <a href="https://github.com/victoryloser/tax-task-agent/blob/main/docs/data-format.md">Data format</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/invoice-trace-evaluator"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-evaluation.svg" width="80" height="80" alt="Invoice Trace Evaluator" /></a></td>
<td valign="top">
<p><sub>03 / EVALUATION</sub></p>
<h3><a href="https://github.com/victoryloser/invoice-trace-evaluator">Invoice Trace Evaluator</a></h3>
<p>Reconstruct invoice-agent traces, locate first faults, and compare two versions using event evidence.</p>
<p>Temporal state · Root causes · Interactive timeline</p>
<p><code>Pydantic</code> <code>JSON Schema</code> <code>Jinja2</code></p>
<p><a href="https://github.com/victoryloser/invoice-trace-evaluator#readme">Documentation</a> · <a href="https://github.com/victoryloser/invoice-trace-evaluator/blob/main/docs/data-format.md">Trace format</a></p>
</td>
</tr>
<tr>
<td width="104" align="center" valign="middle"><a href="https://github.com/victoryloser/medical-agent-platform"><img src="https://raw.githubusercontent.com/victoryloser/victoryloser/main/assets/project-documents.svg" width="80" height="80" alt="Medical Agent Platform" /></a></td>
<td valign="top">
<p><sub>04 / DOCUMENTS</sub></p>
<h3><a href="https://github.com/victoryloser/medical-agent-platform">Medical Agent Platform</a></h3>
<p>Connect medical-document processing with retrieval, asynchronous jobs, and human review.</p>
<p>OCR and de-identification · Hybrid RAG · Graph retrieval</p>
<p><code>FastAPI</code> <code>Milvus</code> <code>Neo4j</code></p>
<p><a href="https://github.com/victoryloser/medical-agent-platform#readme">Documentation</a> · <a href="https://github.com/victoryloser/medical-agent-platform/blob/main/docs/medical-architecture.md">Architecture</a></p>
</td>
</tr>
</table>

Project documentation covers supported inputs, setup, and usage boundaries.

## Engineering focus

- **Visible evidence:** inspect calculations, retrieved sources, and event-level findings.
- **Controlled execution:** organize work through explicit state, permissions, and persistent tasks.
- **Reproducible setup:** document input formats, offline checks, and practical startup steps.

## Toolbox

| Area | Technologies |
|---|---|
| Applications and workflows | `Python` · `FastAPI` · `LangGraph` · `Gradio` · `Streamlit` |
| Data and retrieval | `DuckDB` · `SQLite` · `PostgreSQL` · `Milvus` · `Neo4j` |
| Contracts and evaluation | `Pydantic` · `JSON Schema` · `pytest` |

## More work

- [Annotation Data Tools](https://github.com/victoryloser/process_data): LabelMe merging and filtering, segmentation masks, and image-format utilities.
- [Agent Runtime Kit](https://github.com/victoryloser/agent-runtime-kit): forked from [zed123214/kitagent](https://github.com/zed123214/kitagent).

---

Questions and suggestions are welcome in the relevant repository's issues.
