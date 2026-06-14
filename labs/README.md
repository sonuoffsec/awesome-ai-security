# AI Security Labs

> Hands-on AI security training environments.
> Every lab entry includes difficulty, deployment method, and what you'll learn.

---

## Quick Start - DVAP

The fastest way to get hands-on AI security experience:

```bash
git clone https://github.com/sonuoffsec/dvap
cd dvap
docker compose up -d
# Open http://localhost:8080
```

---

## Lab Catalog

### Prompt Injection Labs

| Lab | Description | Difficulty | Deploy | Link |
|---|---|---|---|---|
| **DVAP** - Prompt Injection Module | Multi-scenario direct and indirect injection training | Beginner–Advanced | Docker | [GitHub](https://github.com/sonuoffsec/dvap) |
| **Gandalf** | Classic password-guarding LLM - bypass 8 levels of guardrails | Beginner | Web | [Play](https://gandalf.lakera.ai) |
| **Prompt Airlines** | Gamified booking AI with injection challenges | Beginner | Web | [Play](https://promptairlines.com) |
| **PortSwigger LLM Labs** | Web Security Academy's LLM attack module | Beginner–Intermediate | Web | [Labs](https://portswigger.net/web-security/llm-attacks) |
| **Learn Prompting - Hackaprompt** | Interactive injection learning platform | Beginner | Web | [Platform](https://learnprompting.org/docs/prompt_hacking/injection) |
| **Crucible** (Dreadnode) | 50+ AI red team challenges including injection | Intermediate–Advanced | Web | [Platform](https://crucible.dreadnode.io) |

### RAG Security Labs

| Lab | Description | Difficulty | Deploy | Link |
|---|---|---|---|---|
| **DVAP** - RAG Module | Document poisoning, retrieval manipulation, exfiltration | Intermediate | Docker | [GitHub](https://github.com/sonuoffsec/dvap) |
| **Build Your Own** | Use the [RAG Security Cheat Sheet](../cheatsheets/rag-security.md) to build a vulnerable RAG instance | Advanced | Python | Custom |

### Agent Security Labs

| Lab | Description | Difficulty | Deploy | Link |
|---|---|---|---|---|
| **DVAP** - Agent Module | Tool poisoning, goal hijacking, memory poisoning scenarios | Intermediate–Advanced | Docker | [GitHub](https://github.com/sonuoffsec/dvap) |
| **AgentDojo** | Benchmark for agent task hijacking via injection | Advanced | Python | [GitHub](https://github.com/ethz-spylab/agentdojo) |
| **AgentBench** | Comprehensive agent behavior and safety evaluation | Advanced | Python | [GitHub](https://github.com/THUDM/AgentBench) |

### MCP Security Labs

| Lab | Description | Difficulty | Deploy | Link |
|---|---|---|---|---|
| **DVAP** - MCP Module | Tool poisoning, schema injection, rug pull attacks | Intermediate | Docker | [GitHub](https://github.com/sonuoffsec/dvap) |
| **MCP Inspector** | Official MCP debugging tool - inspect any server | Beginner | NPX | [GitHub](https://github.com/modelcontextprotocol/inspector) |

### LLM Red Team Platforms

| Platform | Description | Type | Link |
|---|---|---|---|
| **HackAPrompt** | World's largest prompt injection competition - all levels | Competition | [hackaprompt.com](https://www.hackaprompt.com) |
| **Crucible** | Ongoing AI red team challenge platform by Dreadnode | Platform | [crucible.dreadnode.io](https://crucible.dreadnode.io) |
| **AI Village @ DEF CON** | Annual AI security competition (world's largest) | Annual Competition | [aivillage.org](https://aivillage.org) |
| **Haize Labs** | AI red teaming research and evaluation | Research | [haizelabs.com](https://haizelabs.com) |
| **CyberNative AI** | AI security competition platform | Platform | [cybernative.ai](https://cybernative.ai) |

### Training Platforms

| Platform | Description | Level | Link |
|---|---|---|---|
| **PortSwigger Web Security Academy** | LLM attacks module with hands-on labs | Beginner–Intermediate | [PortSwigger](https://portswigger.net/web-security/llm-attacks) |
| **TryHackMe AI Rooms** | Guided AI security rooms | Beginner | [TryHackMe](https://tryhackme.com) |
| **SANS AI Security** | Professional AI security training | Intermediate–Advanced | [SANS](https://www.sans.org) |

---

## Lab Difficulty Guide

| Level | What to Expect |
|---|---|
| **Beginner** | Guided, hints available, no prior AI security knowledge needed |
| **Intermediate** | Some knowledge of AI/LLM architecture required, less guidance |
| **Advanced** | Deep technical knowledge required, real-world complexity |

---

## Self-Hosted Lab Setup Guide

Want to run your own AI security lab environment?

### Minimal Setup (DVAP only)

```bash
# Prerequisites: Docker + Docker Compose
git clone https://github.com/sonuoffsec/dvap
cd dvap
docker compose up -d
```

### Full Lab Environment

```bash
# 1. DVAP (core lab)
git clone https://github.com/sonuoffsec/dvap && cd dvap && docker compose up -d

# 2. AgentDojo (agent security)
pip install agentdojo

# 3. Garak (LLM vulnerability scanner)
pip install garak

# 4. PyRIT (red team toolkit)
pip install pyrit
```

---

## Contributing Labs

Found a vulnerable AI environment we should catalog?
See [CONTRIBUTING.md](../CONTRIBUTING.md) and open an issue with label `lab`.

Requirements for inclusion:
- Freely accessible or self-hostable
- Clear AI security training value
- Actively maintained or stable
- Documented deployment method
