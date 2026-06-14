# AI Security Research Database

> Curated papers, blogs, talks, and reports that define the AI security field.
> Maintained by the community — [contribute a resource](../CONTRIBUTING.md).

---

## Foundational Papers

### Prompt Injection

| Paper | Authors | Year | Venue | Link |
|---|---|---|---|---|
| Prompt Injection Attacks and Defenses in LLM-Integrated Applications | Liu et al. | 2023 | arXiv | [arXiv:2310.12815](https://arxiv.org/abs/2310.12815) |
| Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications | Greshake et al. | 2023 | arXiv | [arXiv:2302.12173](https://arxiv.org/abs/2302.12173) |
| Indirect Prompt Injection: Attacks on LLMs via Retrieved Content | Greshake et al. | 2023 | AISec | [arXiv:2302.12173](https://arxiv.org/abs/2302.12173) |
| Injecting Relevance Feedback into Multi-Stage Retrieval Attacks | Various | 2024 | arXiv | [arXiv](https://arxiv.org) |

### Jailbreaking

| Paper | Authors | Year | Venue | Link |
|---|---|---|---|---|
| Many-Shot Jailbreaking | Anil, Ghosh et al. | 2024 | Anthropic | [Anthropic](https://www.anthropic.com/research/many-shot-jailbreaking) |
| Universal and Transferable Adversarial Attacks on Aligned Language Models | Zou et al. | 2023 | arXiv | [arXiv:2307.15043](https://arxiv.org/abs/2307.15043) |
| Jailbroken: How Does LLM Safety Training Fail? | Wei et al. | 2023 | NeurIPS | [arXiv:2307.02483](https://arxiv.org/abs/2307.02483) |
| "Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts | Shen et al. | 2024 | CCS | [arXiv:2308.03825](https://arxiv.org/abs/2308.03825) |
| ArtPrompt: ASCII Art-based Jailbreak Attacks | Jiang et al. | 2024 | arXiv | [arXiv:2402.11753](https://arxiv.org/abs/2402.11753) |
| Many-shot Jailbreaking via Token Budget | Various | 2024 | arXiv | [arXiv](https://arxiv.org) |

### Training Data Attacks

| Paper | Authors | Year | Venue | Link |
|---|---|---|---|---|
| Extracting Training Data from Large Language Models | Carlini et al. | 2021 | USENIX Security | [arXiv:2012.07805](https://arxiv.org/abs/2012.07805) |
| Poisoning Web-Scale Training Datasets is Practical | Carlini et al. | 2023 | S&P | [arXiv:2302.10149](https://arxiv.org/abs/2302.10149) |
| Backdoor Attacks on Language Models | Wallace et al. | 2021 | EMNLP | [arXiv:2006.01043](https://arxiv.org/abs/2006.01043) |

### Agent Security

| Paper | Authors | Year | Venue | Link |
|---|---|---|---|---|
| AgentDojo: A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents | Debenedetti et al. | 2024 | arXiv | [arXiv:2406.13352](https://arxiv.org/abs/2406.13352) |
| Compromising LLM-Based Applications through Prompt Injection Attacks on Tools | Various | 2024 | arXiv | [arXiv](https://arxiv.org) |
| InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated LLM Agents | Zhan et al. | 2024 | arXiv | [arXiv:2403.02691](https://arxiv.org/abs/2403.02691) |

### RAG Security

| Paper | Authors | Year | Venue | Link |
|---|---|---|---|---|
| PoisonedRAG: Knowledge Corruption Attacks to RAG | Zou et al. | 2024 | arXiv | [arXiv:2402.07867](https://arxiv.org/abs/2402.07867) |
| Phantom: General Trigger Attacks on Retrieval Augmented Language Generation | Chaudhari et al. | 2024 | arXiv | [arXiv:2405.20485](https://arxiv.org/abs/2405.20485) |
| BadRAG: Identifying Vulnerabilities in Retrieval Augmented Generation | Xue et al. | 2024 | arXiv | [arXiv:2406.00083](https://arxiv.org/abs/2406.00083) |

---

## Industry Reports & Standards

| Report | Organization | Year | Link |
|---|---|---|---|
| OWASP Top 10 for LLM Applications | OWASP | 2023–2025 | [OWASP](https://owasp.org/www-project-top-10-for-large-language-model-applications/) |
| OWASP Top 10 for Agentic AI | OWASP | 2025 | [OWASP](https://owasp.org/www-project-top-10-for-llm-applications/docs/agents/) |
| AI Red Team Report | Microsoft | 2023 | [Microsoft](https://www.microsoft.com/en-us/security/blog/ai-red-team) |
| Securing LLM Systems Against Prompt Injection | NCSC UK | 2024 | [NCSC](https://www.ncsc.gov.uk) |
| AI Security Guidelines | NIST | 2023–2024 | [NIST](https://www.nist.gov/artificial-intelligence) |
| Responsible AI Practices | Google DeepMind | 2024 | [DeepMind](https://deepmind.google) |
| Claude's Constitution | Anthropic | 2023 | [Anthropic](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback) |

---

## Must-Read Blogs

| Post | Author/Org | Topic | Link |
|---|---|---|---|
| Prompt injection: what's the worst that can happen? | Simon Willison | PI fundamentals | [Blog](https://simonwillison.net/2023/Apr/14/worst-that-can-happen/) |
| Delimiters won't save you from prompt injection | Simon Willison | PI defenses | [Blog](https://simonwillison.net/2023/May/11/delimiters-wont-save-you/) |
| AI hacking at DEF CON 31 | Kai Greshake | Red teaming | [Blog](https://kai.fyi) |
| MCP Security Overview | Invariant Labs | MCP attacks | [Blog](https://invariantlabs.ai/blog/mcp-security) |
| Securing RAG Applications | LangChain | RAG defense | [Blog](https://blog.langchain.dev) |
| How we red team AI | Microsoft | Red teaming methodology | [Blog](https://www.microsoft.com/en-us/security/blog/ai-red-team) |
| OWASP LLM AI Cybersecurity & Governance | OWASP | Governance | [Blog](https://owasp.org) |

---

## Conference Tracks to Follow

| Conference | AI Security Track | Frequency |
|---|---|---|
| **DEF CON AI Village** | Dedicated AI security village | Annual (August) |
| **Black Hat USA/Europe** | AI-related briefings | Annual |
| **IEEE SaTML** | AI security academic conference | Annual |
| **USENIX Security** | ML security papers | Annual |
| **NeurIPS** | AI safety and robustness | Annual |
| **ACM CCS** | LLM security papers | Annual |
| **BSides** (various cities) | AI security community talks | Ongoing |

---

## Newsletters & Feeds

| Newsletter | Focus | Link |
|---|---|---|
| **tl;dr sec** | General security including AI | [tldrsec.com](https://tldrsec.com) |
| **Lakera Blog** | AI security | [lakera.ai/blog](https://www.lakera.ai/blog) |
| **Invariant Labs Blog** | Agent & MCP security | [invariantlabs.ai](https://invariantlabs.ai) |
| **Simon Willison's Blog** | Prompt injection research | [simonwillison.net](https://simonwillison.net) |
| **The AI Security Digest** | Weekly AI security news | Search on LinkedIn/Substack |

---

## Contributing Research

Know a paper, blog, or talk that belongs here?
Open a PR with label `research` — see [CONTRIBUTING.md](../CONTRIBUTING.md).

Format:
```markdown
| Title | Author(s) | Year | Venue | [Link](url) |
```
