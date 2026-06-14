# AI Security Learning Paths

> Structured journeys from zero to AI security expert.
> Each path is curated - not just a list of links.

---

## Choose Your Path

| Path | Time | Starting Point | Goal |
|---|---|---|---|
| [Beginner](#beginner-path) | 4–6 weeks | No prior AI security knowledge | Understand fundamentals, complete first CTF |
| [Intermediate](#intermediate-path) | 6–10 weeks | Web security background | Specialize in RAG, Agent, or MCP security |
| [Advanced](#advanced-path) | Ongoing | Security professional | AI red team lead, researcher, or tool builder |

---

## Beginner Path

### AI Security Foundations

**Estimated time: 4–6 weeks**

#### Week 1–2: Understand AI Systems

```
Goals:
  ✓ Understand how LLMs work at a high level
  ✓ Learn what prompt injection is and why it matters
  ✓ Complete your first hands-on challenge

Resources:
  □ Read: OWASP LLM Top 10 (all 10 items)
      → https://owasp.org/www-project-top-10-for-large-language-model-applications/
  
  □ Read: "What is Prompt Injection?" (Simon Willison)
      → https://simonwillison.net/2023/Apr/14/worst-that-can-happen/
  
  □ Watch: 3Blue1Brown "But what is a GPT?" (YouTube)
      → Understand transformer architecture visually
  
  □ Play: Gandalf (all 8 levels)
      → https://gandalf.lakera.ai
      → Goal: bypass each level's guardrails
```

#### Week 3–4: First Hands-On Labs

```
Goals:
  ✓ Experience direct and indirect prompt injection
  ✓ Understand how attackers target AI applications
  ✓ Use DVAP for structured training

Resources:
  □ Deploy DVAP:
      git clone https://github.com/sonuoffsec/dvap
      docker compose up -d
  
  □ Complete DVAP Prompt Injection Module (all scenarios)
  
  □ Read: Prompt Injection Cheat Sheet
      → cheatsheets/prompt-injection.md (this repo)
  
  □ Try: Prompt Airlines
      → https://promptairlines.com
```

#### Week 5–6: Broaden & Connect

```
Goals:
  ✓ Complete a beginner CTF
  ✓ Understand the full LLM attack taxonomy
  ✓ Join the AI security community

Resources:
  □ Complete: PortSwigger LLM Labs (all beginner labs)
      → https://portswigger.net/web-security/llm-attacks
  
  □ Read: OWASP LLM Application Security Verification Standard
  
  □ Join: GitHub Discussions in this repo
  
  □ Make your first contribution to this hub (good-first-issue)
```

**Checkpoint:** Can you bypass a simple prompt injection guardrail?
Can you explain what OWASP LLM Top 10 LLM01 is? You're ready for intermediate.

---

## Intermediate Path

### Specialist Tracks

**Estimated time: 6–10 weeks**
**Prerequisites:** Basic web security knowledge, completed beginner path or equivalent

Choose one or more specialist tracks:

---

### Track A: RAG Security Specialist

```
Week 1: RAG Architecture
  □ Read: How RAG systems work (architecture deep dive)
  □ Build: Simple RAG app with LangChain or LlamaIndex
  □ Read: RAG Security Cheat Sheet (this repo)
  □ Goal: understand the full RAG pipeline and each attack surface

Week 2-3: Offensive RAG
  □ Complete: DVAP RAG Module (all scenarios)
  □ Read: PoisonedRAG paper (arXiv:2402.07867)
  □ Practice: Document poisoning against your own RAG app
  □ Practice: Retrieval manipulation and data exfiltration
  □ Read: payloads/rag-attacks/ (this repo)

Week 4: Defensive RAG
  □ Read: RAG hardening best practices
  □ Implement: Secure RAG with proper context labeling
  □ Test: Can you attack your hardened RAG?
  □ Write: Brief report on what worked and what didn't

Week 5-6: Advanced & Research
  □ Read: BadRAG, Phantom papers
  □ Explore: Multi-tenant isolation bypass techniques
  □ Contribute: Add a new RAG attack to this hub's payloads/
```

---

### Track B: Agent Security Specialist

```
Week 1: Agent Architecture
  □ Read: How LLM agents work (tool calling, planning, memory)
  □ Build: Simple agent with tool access (Python + any framework)
  □ Read: Agent Security Cheat Sheet (this repo)
  □ Goal: understand the agent threat model

Week 2-3: Offensive Agent Security
  □ Complete: DVAP Agent Module
  □ Install and run: AgentDojo
      pip install agentdojo
  □ Practice: Goal hijacking via injected instructions
  □ Practice: Tool poisoning - create a malicious tool definition
  □ Read: payloads/agent-attacks/ (this repo)

Week 4: Multi-Agent & Memory Attacks
  □ Read: "InjecAgent" paper (arXiv:2403.02691)
  □ Practice: Multi-agent attack scenarios in AgentDojo
  □ Practice: Memory poisoning in memory-enabled agent

Week 5-6: Defensive & Research
  □ Implement: Human-in-the-loop for sensitive agent actions
  □ Implement: Tool definition auditing
  □ Contribute: Add a new agent attack to this hub's payloads/
```

---

### Track C: MCP Security Specialist

```
Week 1: MCP Fundamentals
  □ Read: MCP Specification (modelcontextprotocol.io)
  □ Install: MCP Inspector and connect to a test server
  □ Read: MCP Security Cheat Sheet (this repo)
  □ Read: mcp/ section of this repo

Week 2-3: MCP Exploitation
  □ Complete: DVAP MCP Module
  □ Run: mcp-scan against available MCP servers
      pip install mcp-scan
  □ Practice: Tool description poisoning (create a malicious server)
  □ Practice: Tool output injection
  □ Read: payloads/mcp-attacks/ (this repo)

Week 4: Advanced MCP Attacks
  □ Practice: Cross-server privilege escalation
  □ Practice: Rug pull attack simulation
  □ Read: Invariant Labs MCP security research

Week 5-6: Defensive & Research
  □ Implement: Secure MCP server with proper tool definitions
  □ Contribute: Add a new MCP attack to this hub's mcp/ section
```

---

## Advanced Path

### Expert & Researcher Track

**Prerequisites:** Security professional background, completed intermediate path

#### Module 1: AI Red Team Methodology

```
□ Read: Microsoft AI Red Team methodology
□ Read: AI Red Team Cheat Sheet (this repo)
□ Study: PyRIT framework - full documentation
□ Build: Custom red team automation pipeline
□ Complete: Advanced Crucible challenges
□ Goal: Lead an AI red team engagement end-to-end
```

#### Module 2: Original Research

```
□ Read: 5+ foundational papers (see research/README.md)
□ Identify: A gap in the current AI security literature
□ Build: A novel attack technique or detection method
□ Test: Against multiple production AI systems (authorized)
□ Publish: Write-up, blog, or paper
□ Contribute: Add your research to research/README.md
```

#### Module 3: Tool Building

```
□ Study: Garak codebase - how automated LLM probing works
□ Study: PyRIT codebase - red team orchestration patterns
□ Build: A tool that solves an AI security problem you've identified
□ Open source: Release under a permissive license
□ Contribute: Add to tools/README.md
```

#### Module 4: Community Leadership

```
□ Write: Technical blog posts sharing your research
□ Speak: Submit to DEF CON AI Village, Black Hat, or BSides
□ Mentor: Help beginners in this hub's GitHub Discussions
□ Contribute: Regular contributions to this hub
□ Build: Your own AI security CTF challenge
```

---

## Additional Resources

### Books

| Title | Authors | Focus |
|---|---|---|
| *Hacking AI* (upcoming) | Various | AI penetration testing |
| *Security Engineering* | Ross Anderson | Security fundamentals applicable to AI |

### Certifications

| Cert | Provider | Relevance |
|---|---|---|
| GAISP (in development) | GIAC | AI security professional |
| SANS AI Security courses | SANS | Professional training |

### Communities

| Community | Platform | Link |
|---|---|---|
| AI Village | Discord / DEF CON | [aivillage.org](https://aivillage.org) |
| AI Security Hub | GitHub Discussions | [This repo](https://github.com/sonuoffsec/awesome-ai-security/discussions) |
| r/netsec | Reddit | [r/netsec](https://reddit.com/r/netsec) |
