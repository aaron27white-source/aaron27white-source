# Aaron White

**AI Agent Engineer** · Houston, TX

I build agents that run on their own, do real work, and get measured. If an agent doesn't earn its cost, it gets switched off.
I also run live AV production at a major Houston hotel, where the system has to work the first time in front of a full room. I build software with the same rule.

## ⭐ Featured: [Oleflip Ops Terminal](https://github.com/aaron27white-source/oleflip-ops-terminal)

An AI-driven operations terminal for an IT-parts reselling business, with an **autonomous 8-agent back office**.

- **8 agents on a cron scheduler:** scanner, pricer, listings, inventory, customer, research, marketing and auditor
- **One LLM client, 4 providers:** Claude, OpenAI, DeepSeek and Grok
- **Every run logged** with tokens and cost. **Per-agent daily budget caps** and on/off switches
- **Weekly Auditor agent** scores the other seven from their run history and *proposes* prompt fixes, which a human approves before they go live
- FastAPI + SQLite backend, Next.js + Tailwind PWA, pluggable pricing engine, Discord/Slack/Web Push alerts
- Runs locally with **no API keys** on a bundled open engine and synthetic data

## 🔧 Also built

- **Blanco OS** (private): my own multi-agent ops platform. FastAPI, 171+ tests, and chat routing to a local agent gateway or headless Claude Code
- **[AI Business Automator](https://github.com/aaron27white-source/ai-business-automator):** replaced 4 fragile n8n workflows with one FastAPI service for LLM email classification, lead enrichment and auto-replies
- **[IT Inventory Tracker](https://github.com/aaron27white-source/it-inventory-tracker):** asset-management REST API with an audit trail and CSV import/export
- **[ETL Pipeline](https://github.com/aaron27white-source/etl-pipeline):** CLI data pipeline with run tracking and error observability

## 🛠 Stack

**Agents & LLMs:** Claude, OpenAI, DeepSeek, Grok, OpenRouter, Claude Code, multi-agent orchestration, voice agents (Vapi, ElevenLabs)
**Backend:** Python, FastAPI, SQLite, REST APIs, pytest
**Frontend:** TypeScript, Next.js, React, Tailwind
**Infra:** Cloudflare (Workers, D1, Pages), Docker, Linux, NGINX
**Security habits:** gitleaks, semgrep, server-side authz

## 📜 Certifications

- ✅ Anthropic AI Fluency · Anthropic Claude 101 · Audinate Dante Level 1
- 🔜 AWS Solutions Architect Associate · CCNA

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/aaron-white-b4b197331) · [key20co.com](https://key20co.com) · aaron27white@gmail.com
