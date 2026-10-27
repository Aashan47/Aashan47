## Hi, I'm Aashan

I'm an AI engineer. I build agents and ML systems that hold up in production, with a focus on reliability: evals, guardrails, calibrated uncertainty and observability.

At [FortyGuard](https://fortyguard.com), a climate tech startup headquartered in Abu Dhabi (I work remotely from Pakistan), I work on street-level air temperature models and geospatial multi-agent systems.

### Recent work

- **[holdline](https://github.com/Aashan47/holdline)** · [product page](https://www.aashanjaved.com/holdline/) · `pip install holdline`<br>
  Open-source eval and regression gate for AI agents. It checks the path an agent took, not only its answer, reports pass^k across repeated runs, measures an LLM judge against human labels before trusting it, and fails the pull request when a change makes the agent measurably worse (paired McNemar and bootstrap). Zero dependencies; runs as a GitHub Action.

- **[helpdesk-agent](https://github.com/Aashan47/helpdesk-agent)**<br>
  A support agent that replies only from the help centre, cites the article it used, and escalates to a human when it is not confident. The threshold is calibrated with conformal prediction. On 41 held-out tickets: 0% wrong replies on questions the help centre does not cover, 96.4% reply accuracy, 68.3% resolved without a human.

- **[heatline](https://github.com/Aashan47/heatline)** · [live](https://heat.aashanjaved.com)<br>
  Is an outdoor worker in Karachi over the heat limit right now? Wet-bulb globe temperature from public forecasts, checked hourly against NIOSH work limits. Its agent declines when the data cannot support an answer.

- **[Turno](https://github.com/Aashan47/turno)** · [live](https://turno.aashanjaved.com)<br>
  Shift planning for outdoor crews under Italian heat ordinances. It reads the signed ordinance PDF, quotes it verbatim for every rule it applies, and hands the hours it cannot decide to the supervisor. Built for the AMD Developer Hackathon ACT III.

- **[Fail Closed](https://github.com/Aashan47/fail-closed)**<br>
  Four coding agents divided by authority, where no agent both produces evidence and accepts it. Built solo for the Dark Factory hackathon.

### Earlier projects

[Visual Research Assistant](https://github.com/Aashan47/Visual-Research-Assistant-Multimodal-Agentic-RAG) (multimodal agentic RAG) · [Beijing air-quality forecasting](https://github.com/Aashan47/Beijing-Air-Quality-Forecasting-MLOps-Pipeline) (MLOps pipeline) · [Hotel search learning-to-rank](https://github.com/Aashan47/Production-Learning-to-Rank-LTR-System-Hotel-Search-Ranking) (NDCG@5 +9.5%) · [AlphaEarth climate monitoring](https://github.com/Aashan47/Alpha-Earth---Climate-Monitoring-System) · [Urban data-center siting](https://github.com/Aashan47/Urban-Data-Center-Site-and-Risk-Assessment)

### Research

Independent research on calibrated uncertainty under distribution shift (2025 to present). Under review at AISTATS 2027: *How Fine Can Your Groups Get? The Breakdown of Plug-in Worst-Group Accuracy*.

### Stack

- **Agents:** tool-use loops, guardrails, human-in-the-loop hand-off, evals and CI eval gates, observability, RAG
- **AI and ML:** Python, PyTorch, Gemini, Claude, GPT, LangChain, embeddings, conformal prediction, XGBoost
- **Backend and infra:** FastAPI, Postgres, Docker, AWS, GCP, Azure, GitHub Actions, Linux/systemd, Airflow, MLflow

### Find me

[aashanjaved.com](https://aashanjaved.com) · [LinkedIn](https://www.linkedin.com/in/aashan-javed/) · aashanjaved.cs@gmail.com
