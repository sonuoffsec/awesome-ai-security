# AI Security CTF Challenges

> Competitive AI security challenges — ordered by skill level.
> Test your skills against real AI security scenarios.

---

## Active CTF Platforms

### Always-On Platforms

| Platform | Challenges | Level | Topics | Link |
|---|---|---|---|---|
| **Gandalf** (Lakera) | 8+ levels + sandbagging | Beginner | Prompt injection, guardrail bypass | [gandalf.lakera.ai](https://gandalf.lakera.ai) |
| **Crucible** (Dreadnode) | 50+ challenges | Beginner–Expert | Full AI red team spectrum | [crucible.dreadnode.io](https://crucible.dreadnode.io) |
| **Prompt Airlines** | Multiple scenarios | Beginner | Prompt injection, booking AI abuse | [promptairlines.com](https://promptairlines.com) |
| **PortSwigger LLM Labs** | 10+ guided labs | Beginner–Intermediate | Injection, data exfiltration, plugins | [portswigger.net](https://portswigger.net/web-security/llm-attacks) |
| **DVAP** | Ongoing scenarios | Beginner–Advanced | Full stack AI security | [GitHub](https://github.com/sonuoffsec/dvap) |

---

## Competition CTFs

### HackAPrompt

| Field | Detail |
|---|---|
| **Description** | World's largest prompt injection competition |
| **Organizer** | Learn Prompting |
| **Level** | Beginner → Advanced |
| **Topics** | Prompt injection, guardrail bypass, LLM manipulation |
| **Format** | Multi-level, scored challenges |
| **Website** | [hackaprompt.com](https://www.hackaprompt.com) |

### AI Village @ DEF CON

| Field | Detail |
|---|---|
| **Description** | The world's largest AI security competition, held annually at DEF CON |
| **Level** | Intermediate → Advanced |
| **Topics** | Red teaming LLMs, adversarial ML, AI system exploitation |
| **Format** | Annual, team-based |
| **Website** | [aivillage.org](https://aivillage.org) |
| **Notable** | DEF CON AI Village has featured challenges against production models from major AI companies |

### SaTML CTF (IEEE)

| Field | Detail |
|---|---|
| **Description** | Academic AI security competition at IEEE SaTML conference |
| **Level** | Advanced |
| **Topics** | LLM red teaming, safety bypass, adversarial attacks |
| **Format** | Annual competition |
| **Website** | [satml.org](https://satml.org) |

### LLM CTF @ TCB

| Field | Detail |
|---|---|
| **Description** | Capture the Flag focused on LLM attack and defense |
| **Level** | Intermediate–Advanced |
| **Topics** | Prompt injection, jailbreaking, data extraction |
| **Format** | Team competition |

### CyberNative AI CTF

| Field | Detail |
|---|---|
| **Description** | AI-focused security challenges |
| **Level** | Intermediate |
| **Topics** | LLM manipulation, agent security |
| **Website** | [cybernative.ai](https://cybernative.ai) |

---

## Challenge Categories

### Prompt Injection Challenges

| Skill Level | What You'll Practice |
|---|---|
| Beginner | Basic instruction override, simple bypass |
| Intermediate | Multi-turn injection, indirect injection via retrieved content |
| Advanced | Chained injection, multi-modal injection, automated injection |

### Agent Security Challenges

| Skill Level | What You'll Practice |
|---|---|
| Intermediate | Tool manipulation, goal hijacking |
| Advanced | Multi-agent attacks, persistent memory poisoning, autonomous exploitation |

### Jailbreaking Challenges

| Skill Level | What You'll Practice |
|---|---|
| Beginner | Roleplay bypass, simple encoding |
| Intermediate | Many-shot, authority impersonation |
| Advanced | Novel techniques, automated fuzzing, model-specific exploits |

### RAG/Knowledge Base Challenges

| Skill Level | What You'll Practice |
|---|---|
| Intermediate | Document poisoning, retrieval manipulation |
| Advanced | Embedding attacks, cross-tenant exfiltration |

---

## CTF Tips & Resources

### Getting Started

```
1. Start with Gandalf — free, always available, great for learning
2. Work through PortSwigger LLM labs — structured learning path
3. Join Crucible for ongoing challenges
4. Work up to HackAPrompt competition
5. Aim for AI Village @ DEF CON
```

### Tools for AI CTFs

| Tool | Use Case |
|---|---|
| **Burp Suite** | Intercept and modify requests to LLM APIs |
| **Python + OpenAI/Anthropic SDK** | Automate attack attempts |
| **Garak** | Automated LLM vulnerability probing |
| **DVAP** | Practice specific techniques in controlled environment |

### Writeup Resources

| Resource | Link |
|---|---|
| HackAPrompt Writeups | [GitHub discussions](https://github.com/trigaten/Prompt-Hacking) |
| Lakera AI Blog | [Lakera Blog](https://www.lakera.ai/blog) |
| Simon Willison (PI research) | [simonwillison.net](https://simonwillison.net/search/?q=prompt+injection) |
| AI Security Newsletter | [tl;dr sec](https://tldrsec.com) |

---

## Create Your Own AI CTF

Want to host an AI security CTF challenge?

Resources:
- **DVAP** provides pre-built challenge modules you can host: [GitHub](https://github.com/sonuoffsec/dvap)
- **CTFd** framework works well for AI security challenges: [ctfd.io](https://ctfd.io)
- See [CONTRIBUTING.md](../CONTRIBUTING.md) to add your CTF to this list

---

## Hall of Fame

> Top AI security CTF performers and notable achievements.
> [Submit your CTF achievement via PR](../CONTRIBUTING.md)

*Be the first to add yours here.*
