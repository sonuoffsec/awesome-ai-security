# AI Security Tools

> The most comprehensive catalog of AI security tooling.
> Open source preferred. Commercial tools included if widely used or have free tier.

---

## Quick Reference

| Category | Top Tools |
|---|---|
| Prompt Injection Testing | Garak, PyRIT, promptmap, LLMFuzzer, rebuff |
| Red Teaming | PyRIT, PromptBench, HarmBench, JailbreakBench |
| Jailbreak Evaluation | HarmBench, JailbreakBench, StrongREJECT |
| Guardrails | NeMo Guardrails, Guardrails AI, LlamaGuard |
| Detection | Rebuff, Lakera Guard, PromptShield |
| Monitoring | LangSmith, Helicone, Lunary, Opik |
| Agent Security | AgentDojo, Invariant Analyzer |
| MCP Security | mcp-scan, Invariant Analyzer, MCP Inspector |
| RAG Security | (See RAG section) |

---

## Prompt Injection Testing

| Tool | Type | Stars | Description | Link |
|---|---|---|---|---|
| **Garak** | Open Source | ⭐ 5k+ | Comprehensive LLM vulnerability scanner with 100+ probes for prompt injection, data leakage, toxicity, and more | [GitHub](https://github.com/NVIDIA/garak) |
| **PyRIT** | Open Source | ⭐ 3k+ | Microsoft's Python Risk Identification Toolkit - orchestrates multi-turn red team attacks | [GitHub](https://github.com/Azure/PyRIT) |
| **promptmap** | Open Source | ⭐ 1k+ | Automated prompt injection testing tool targeting custom GPT instances | [GitHub](https://github.com/utkusen/promptmap) |
| **LLMFuzzer** | Open Source | ⭐ 500+ | Fuzzing framework for LLMs - discovers unexpected behaviors | [GitHub](https://github.com/mnns/LLMFuzzer) |
| **prompt-injection-tester** | Open Source | - | Test suite for prompt injection vulnerabilities | [GitHub](https://github.com) |

### Using Garak

```bash
pip install garak

# Scan a model for prompt injection
garak -m openai -n gpt-4 -p promptinjection

# Full vulnerability scan
garak -m openai -n gpt-4 --parallel 4

# List all available probes
garak --list-probes
```

---

## Red Teaming Frameworks

| Tool | Type | Stars | Description | Link |
|---|---|---|---|---|
| **PyRIT** | Open Source | ⭐ 3k+ | Microsoft's end-to-end red team orchestration for GenAI | [GitHub](https://github.com/Azure/PyRIT) |
| **PromptBench** | Open Source | ⭐ 2k+ | Adversarial robustness evaluation for LLMs (Microsoft) | [GitHub](https://github.com/microsoft/promptbench) |
| **HarmBench** | Open Source | ⭐ 1k+ | Standardized evaluation framework for LLM safety and jailbreaks | [GitHub](https://github.com/centerforaisafety/HarmBench) |
| **JailbreakBench** | Open Source | ⭐ 500+ | Benchmark for comparing jailbreak attack success rates | [GitHub](https://github.com/JailbreakBench/jailbreakbench) |
| **StrongREJECT** | Open Source | - | Robust evaluation for jailbreak resistance | [GitHub](https://github.com) |
| **ArtPrompt** | Open Source | - | ASCII art-based adversarial attack evaluation | [GitHub](https://github.com/uw-nsl/ArtPrompt) |

---

## Guardrails & Input/Output Protection

| Tool | Type | Description | Link |
|---|---|---|---|
| **NeMo Guardrails** | Open Source | NVIDIA's programmable guardrail framework for conversational AI | [GitHub](https://github.com/NVIDIA/NeMo-Guardrails) |
| **Guardrails AI** | Open Source | Validation and correction framework for LLM outputs - define rules, fix violations | [GitHub](https://github.com/guardrails-ai/guardrails) |
| **LlamaGuard** | Open Source | Meta's safety classifier - fine-tuned Llama for I/O classification | [GitHub](https://github.com/meta-llama/PurpleLlama) |
| **Rebuff** | Open Source | Self-hardening prompt injection detection API with heuristics + LLM + vector DB | [GitHub](https://github.com/protectai/rebuff) |
| **Lakera Guard** | Commercial | Real-time prompt injection, PII, toxicity detection API | [Website](https://www.lakera.ai) |
| **Azure PromptShield** | Commercial | Microsoft's prompt injection and jailbreak detection | [Docs](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/) |

---

## Monitoring & Observability

| Tool | Type | Description | Link |
|---|---|---|---|
| **Langfuse** | Open Source | LLM tracing, evaluation, and prompt management | [GitHub](https://github.com/langfuse/langfuse) |
| **Helicone** | Open Source | LLM observability, rate limiting, caching, and security monitoring | [GitHub](https://github.com/Helicone/helicone) |
| **Lunary** | Open Source | LLM monitoring, logging, analytics, and cost tracking | [GitHub](https://github.com/lunary-ai/lunary) |
| **Opik** | Open Source | End-to-end LLM evaluation, tracing, and monitoring (Comet) | [GitHub](https://github.com/comet-ml/opik) |
| **LangSmith** | Commercial | LangChain's LLM tracing, evaluation, and testing platform | [Website](https://smith.langchain.com) |
| **Weights & Biases** | Commercial | ML experiment tracking with LLM evaluation features | [Website](https://wandb.ai) |

---

## Agent Security Tools

| Tool | Type | Description | Link |
|---|---|---|---|
| **AgentDojo** | Open Source | Agent security evaluation - tests agents against injection and task hijacking | [GitHub](https://github.com/ethz-spylab/agentdojo) |
| **Invariant Analyzer** | Open Source | Dynamic analysis of MCP and agent execution traces for security violations | [GitHub](https://github.com/invariantlabs-ai/invariant) |
| **AgentBench** | Open Source | Comprehensive agent capability and safety benchmark | [GitHub](https://github.com/THUDM/AgentBench) |

---

## MCP Security Tools

| Tool | Type | Description | Link |
|---|---|---|---|
| **mcp-scan** | Open Source | Static analysis scanner for MCP server configurations - detects tool poisoning | [GitHub](https://github.com/invariantlabs-ai/mcp-scan) |
| **Invariant Analyzer** | Open Source | Dynamic trace analysis for MCP tool calls | [GitHub](https://github.com/invariantlabs-ai/invariant) |
| **MCP Inspector** | Open Source | Official debugging and inspection tool for MCP servers | [GitHub](https://github.com/modelcontextprotocol/inspector) |

---

## RAG Security Tools

| Tool | Type | Description | Link |
|---|---|---|---|
| **Ragas** | Open Source | RAG evaluation framework - measures faithfulness, relevance, and safety | [GitHub](https://github.com/explodinggradients/ragas) |
| **ARES** | Open Source | Automated RAG evaluation system | [GitHub](https://github.com/stanford-futuredata/ARES) |
| **Garak** (RAG probes) | Open Source | Garak includes probes for RAG-specific vulnerabilities | [GitHub](https://github.com/NVIDIA/garak) |

---

## CTF & Training Tools

| Tool | Type | Description | Link |
|---|---|---|---|
| **DVAP** | Open Source | The official hands-on AI security lab for this hub | [GitHub](https://github.com/sonuoffsec/dvap) |
| **Garak** | Open Source | Use for automated CTF challenge solving and testing | [GitHub](https://github.com/NVIDIA/garak) |

---

## Contributing a Tool

Know a tool that should be here? Open an issue with label `tool` or submit a PR.
See [CONTRIBUTING.md](../CONTRIBUTING.md) for format guidelines.

Requirements:
- Clear AI security use case
- Accessible (open source or free tier available)
- Actively maintained (prefer last commit within 12 months)
