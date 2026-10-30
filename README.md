### Hi, I'm Gitesh 👋

**AI Engineer · Data Scientist** · San Francisco Bay Area

I build LLM agents and data-driven models that are measured, not guessed: retrieval with citations, tools for exact numbers, and eval suites that say when something works.

[🌐 giteshpoudel.com](https://giteshpoudel.com) · [💼 LinkedIn](https://www.linkedin.com/in/gitesh-poudel/) · [✉️ Email](mailto:giteshpoudel@gmail.com)

---

### 🚀 Recent projects

#### [Experimentation Copilot](https://github.com/giteshpoudel/experiment-copilot)
*An AI analyst for A/B tests that never does the math itself.*
An MCP server with 12 typed statistics tools (power, SRM, CUPED, sequential and Bayesian tests, uplift) and an agent that writes ship / don't-ship readouts where every number comes from a tool call.
**98%** of decisions match the pre-registered rule, vs 73% for the same model without tools.
[Case study](https://giteshpoudel.com/projects/experiment-copilot) · [Live demo](https://experiment-copilot-idvwpntu3pan6hk9rrjxfz.streamlit.app)
`Python` `MCP` `Function calling` `DuckDB` `SciPy` `Streamlit`

#### [EDGAR RAG Analyst](https://github.com/giteshpoudel/edgar-rag-analyst)
*An AI agent for SEC filings that cites every claim and computes every number.*
Hybrid search over the 10-K filings of 15 companies, with figures from SEC XBRL data through typed tools and a grounding guard that checks every number. An eval gate runs on every pull request.
**97.5%** pass rate on a held-out test set, at $0.0012 per question.
[Case study](https://giteshpoudel.com/projects/edgar-rag-analyst)
`Python` `RAG` `LanceDB` `Hybrid search` `Evals` `GitHub Actions`

#### [Alpha Research Engine](https://github.com/giteshpoudel/alpha-research-engine)
*Autonomous quant research for crypto, on local infrastructure.*
A sentiment pipeline with local LLM embeddings, ClickHouse and Qdrant storage, and a VectorBT backtesting framework with strict in-sample / out-of-sample separation.
**7** built-in strategies · **~500k** candles · **338** tests.
[Case study](https://giteshpoudel.com/projects/alpha-research-engine)
`Python` `LangGraph` `Optuna` `VectorBT` `ClickHouse` `Qdrant`

---

### 🧰 Toolbox

**AI engineering:** LLM agents & function calling · MCP servers · RAG & hybrid search · LLM evaluation · observability (OpenTelemetry) · CI eval gates

**Data science:** A/B testing · causal inference & uplift · sequential & Bayesian testing · CUPED · Monte Carlo simulation · NLP

**Data & infra:** Python · SQL · Snowflake & dbt · DuckDB · LanceDB · Qdrant · Docker · AWS
