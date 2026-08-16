# 🧠 Lead Intelligence Agentic System

<div align="center">
  <img src="https://img.shields.io/badge/Architecture-Autonomous%20Multi--Agent-blue?style=for-the-badge&logo=openai">
  <img src="https://img.shields.io/badge/Workflow-Signal%20%E2%86%92%20Graph%20%E2%86%92%20Outreach-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-AsyncIO%203.11+-yellow?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</div>

<br>

An autonomous multi-agent pipeline for B2B intelligence and outbound prospecting. Replaces static databases with agentic signal scoring, social graph warm-path mapping, and contextual LLM-driven outreach generation.

---

## 🏗️ Multi-Agent Architecture

```mermaid
flowchart LR
    A[Raw Lead Signal] --> B[Signal Scorer Agent]
    B -->|Score >= 0.60| C[Warm-Path Discovery Agent]
    B -->|Score < 0.60| D[Disqualified]
    C -->|Social Graph Match| E[Mutual Intro Route]
    C -->|No Mutual| F[Contextual Cold Route]
    E --> G[Personalized Outreach Agent]
    F --> G
    G --> H[Final Outbound Dossier]
```

---

## 🌟 Specialized Agents

1. **Signal Scorer Agent:** Evaluates ICP fit (Title authority 30%, Industry match 25%, Intent signals 20%).
2. **Warm-Path Discovery Agent:** Analyzes 1st and 2nd-degree connection graphs to discover high-trust warm introduction bridges.
3. **Personalized Outreach Agent:** Synthesizes intent data into non-templated, contextualized outreach copy.

---

## 🚀 Quickstart

```bash
pip install -r requirements.txt
python -m src.orchestrator
```

---

## 📄 License
MIT License. See `LICENSE` for details.
